## ViewModel

### Theory

As we've seen in the latest video, we have a problem with our App when we rotate the Phone. All values are lost! This suc... is unpleasant. The problem is the lifecycle of our fragment. Each time we rotate the screen, our fragment is stopped and rebuild from scratch. So, the only way to fix it is to store our values somewhere else. In a place which stays even when the fragment is rebuild. Once we have that, we can just reload the stored values into the fragment. And this place is called the viewmodel. This [video](https://www.youtube.com/watch?v=j5ZouactAvk&list=PLlxmoA0rQ-LyVuVR1LFvpR1K8A0HsIBYx&index=4) gives you some more background information. 

In addition to keep our values save, the viewmodel has another advantage. We add another layer to separate our User Interface (Buttons, TextViews) from the logic of our app. In the best case, the user Interface just takes some values from the viewmodel and displays them. It should not be of importance for the fragment what these values mean, it is just something to put in a specific TextView. And the viewmodel provides these values. And we have another layer of this encapsulation. The viewmodel uses objects, it does not need to know how they are implemented. In our case, the viewmodel uses the dice class, but does not care how exactly the random numbers it uses are calculated. 

Together, we have a three layered architecture:
1. The Model (the classes) which implement the logic of the things we are working with.
2. The ViewModel which uses the models to provide information to the UI (but does not know anything about what the UI actually does with this information)
3. The View, which just takes the values from the viemodel and shows them to the user. It does not need to know what these values are and how these are calculated.

Together, these layers build the so called [MVVM (Model-View-ViewModel) Architecture](https://de.wikipedia.org/wiki/Model_View_ViewModel).

### Actions

Let's re-organize our code to follow the MVVM architecture and check, whether we now can rotate our phone.

---

[back](../README.md)