## Data Types

### Theory

In Kotlin, every variable has to know which type of data it is supposed to store. This has the advantage that Kotlin can check already at compile time (when it translates a text to machine executable instructions [yeah, I know, JVM, bare with me...]) whether the programmer tries to do something which might be an error like adding text to a number. The types we will use most frequently are:

- real numbers (Int)
- floating point numbers (Double [or float, if you are sure what you are doing])
- Text (String [or rarely Char])
- True or False [Boolean]

So, if we want to declare a new text variable, we should code `var bee: String = "Maja"`. But wait, didn't we write just `var bee = "Maja"` in the last exercises? Nicely, Kotlin has a feature called "type inference", which "sees" that you wanted the bee variable to hold a text. In this case, you don't have to explicitly state, which type of data your new variable should hold.

You can find more information in the [Data Types Section](https://stepik.org/lesson/104305/step/1?unit=78863) and in [this video](https://www.youtube.com/watch?v=qAJTqI_aKJU&list=PLlxmoA0rQ-LwgK1JsnMsakYNACYGa1cjR). In the video you also learn about the memory consumption of data types, which can influence your decision for one or the other.

And if you want to get a bit deeper into Strings and what you can do with them, watch this [video](https://www.youtube.com/watch?v=n4WBip822A8).

### Action

Work through Exercises 1-5 of the Data Types section.

- In Exercise 1, you have to comment out the line which produces an error and print the error message
- In Exercise 2, comment out the last TODO() after you have used it to find some not working combinations
- In Exercise 3, you might want to check the hint ;-)

---

[back](../README.md)
