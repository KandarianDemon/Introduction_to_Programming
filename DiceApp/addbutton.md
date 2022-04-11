## Buttons

### Theory

In this section, we will add a button to our app. Although the function of a button is always more or less the same - click me and something happens - , buttons can look pretty different. There are [styling guides](https://material.io/components?platform=android) for all types of components. They are pretty useful, when (i) checking what a widget can be used for and (ii) what are the Dos and Donts when working with them. And of course you'll also find some useful tips for our [buttons](https://material.io/components/buttons).

But, we will not only add a button, we will also give it some functionality. To do so, we use a function that comes with buttons, `setOnClickListener()`. The interesting thing here is that this function takes as parameter another function! And this will be executed each time the button is clicked. The whole thing will look like this:

    myButton.setOnClickListener {
        // Code for the actions here
    }

And of course within the code block, you can call other functions again! In the Action section, we will use this to change the text of the button after it was clicked.

### Actions

Watch this [video](https://www.youtube.com/watch?v=4j_ynDzKSw4&list=PLuybLXH6lvUE46CbWWTXahSdi7DVlDuso&index=3) and follow along. And play around with the code.

---

[back](../README.md)