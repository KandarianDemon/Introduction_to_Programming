## TextView

### Theory

To just display some text in your App, you can use a TextView widget. You've seen in the previous section, how you can change a text of a TextView in the UI Editor. Here, you will learn one way to change the text dynamically in your program. Therefore, we have to tell our Kotlin code which widget we want to work with. At the moment, we will get the widget into our code using the `findViewById()` function. As a parameter, it takes the id (name) we gave the widget. Furthermore, we have to tell Kotlin, which type of widget this is. The whole call of the function looks like this:

    view.findViewById<TextView>(R.id.message)

Later in the course we will learn other (cooler?) ways to work with UI widgets.

### Actions

Watch this [video](https://www.youtube.com/watch?v=M1bkakKkkFs&list=PLuybLXH6lvUE46CbWWTXahSdi7DVlDuso&index=2) and follow along.

---

[back](../README.md)