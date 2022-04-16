## View Binding

### Theory

So far, we used the `findViewById` method to interact programmatically with our UI elements. As parameter, took the id os the element, like in `view.findViewById<TextView>(R.id.message)`. Which is ugly, as the id, and therefore the name of the UI element has to be unique over our whole App. Furthermore, we have to explicitly give the type of the UI element. Wouldn't it be nicer, if the program knew, which xml file we are working with at the moment? Plus, if it would know whether we are working with a button or a textfield? I mean, all the information is in the xml file, why not using it?

And this is where [View Binding](https://developer.android.com/topic/libraries/view-binding) comes into the game. To quote the documentation:

> View binding is a feature that allows you to more easily write code that interacts with views.

Nice! So let's implement this!

### Actions

Go to the [documentation](https://developer.android.com/topic/libraries/view-binding#kts). It tells us, that we have to change the module level `build.gradle` file (this is the one where we already added the additional dependency for the viewmodel). In the `android` section, add the following just below `kotlinOptions`

    buildFeatures {
        viewBinding = true
    }

The part should now look like this:

        kotlinOptions {
            jvmTarget = '1.8'
        }
        buildFeatures {
            viewBinding = true
        }
    }

Click on the elephant to sync the changes, and you're ready to go!

Now we can use this new feature in our fragment. The [documentation](https://developer.android.com/topic/libraries/view-binding#fragments) again tells us how. Delete the current version of the `onCreateView` function and paste the one from the documentation. Plus, add the `private vars` as well as the `onDestroyView()` function. You will get an error that it does not know `ResultProfileBinding`. That's because this name is automatically derived from the name of your xml file. In our case the name of the xml file is `main_fragment.xml`, so we have to change `ResultProfileBinding` to `MainFragmentBinding`. And now we are ready to access our UI elements!

Let's start with the textfield. Delete `val textfield = view.findViewById<TextView>(R.id.message)`. In the following line, just add `binding` in front of the now red `textfield`. The line should look like this:

    binding.textfield.text = counter.toString()

That's it! No more messing around with ids of UI elements, no explicit type statement needed! Nice! So now it's up to you. Adopt the code for the other UI elements in the fragment!
`

---

[back](../README.md)