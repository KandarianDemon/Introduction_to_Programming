## if Statements (and Booleans)

### Theory

You might want to execute parts of your code only under specifically defined circumstances. This raises two questions we will address in this section: 

1. How can I check that my program is currently in these circumstances?
2. How can I tell my program that given these conditions it should execute some code or not?

The first question is addressed in [this video](https://www.youtube.com/watch?v=BHHFZsiyyno&list=PLQkwcJG4YTCRSQikwhtoApYs9ij_Hc5Z9&index=8). You can find a [full list of operators](https://kotlinlang.org/docs/keyword-reference.html#operators-and-special-symbols) in the Kotlin documentation. If you find these ands and ors and nots and how they can be combined a bit confusing, [these two tables](https://en.wikipedia.org/wiki/Boolean_algebra#Basic_operation) tell you what's the result of these operators depending on the input. Note that Kotlin is clever and evaluates conditions only as long as it is certain about the output. For example if you have a `||` (or) condition, it will start on the left. If this first condition evaluates to true, the result can only be true (re-check the tables to see why). In this case Kotlin (and many other programming languages) will not evaluate the second part.

Now that we know how to check for a condition, you can see how to use it to [conditionally execute code](https://www.youtube.com/watch?v=g5mmLQbnXTQ&list=PLQkwcJG4YTCRSQikwhtoApYs9ij_Hc5Z9&index=9). Note that an if statement can also return a value. In this case, you use the if / else as an expression. In the [Kotlin documentation of the if expression](https://kotlinlang.org/docs/control-flow.html#if-expression), you can see that even have multiple statements in a block and still use it as expression.

### Action

Go over the [if Expression](https://stepik.org/lesson/104307/step/1?unit=78865) section of Atomic Kotlin and then solve the exercises 1-4 in the IDE.

Following, check the [Booleans section](https://stepik.org/lesson/104310/step/1?unit=78868) and solve the exercises 1 and 4. In Exercise 1, substitute the TODO() with true / false.

---

[back](../)
