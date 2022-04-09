## Inheritance

### Theory

Now we know classes, imagine you have two things which are pretty similar, but differ in some aspects. You might think about a mouse and a rat - both rodents, many identical behaviours but if you look closely, there are also some differing behaviours. Right now, you would have to make one `class Mouse`and another `class Rat` and copy code from one to the other. Now, copying code and having the same code in two places is always ugly and hard to maintain. But of course, Kotlin (and all object-oriented programming languages) can help you out here. Instead of having two classes, you generate a base class, say `class Rodents`. Here you describe all properties and methods which are shared between all rodents. Then you only have to tell Kotlin that a rat is a rodent, and it inherits (!) all features of a rodent. In the class rat, you only describe the specifics of a rat.

And here's a [video](https://www.youtube.com/watch?v=Xk3IPNHbLVk&list=PLQkwcJG4YTCRSQikwhtoApYs9ij_Hc5Z9&index=21) on how you translate this idea into Kotlin.

### Actions

Go through Exercises 1-3 of Object-Oriented Programming -> Inheritance. Run them locally, I got some strange compile error when trying to Check it.  

---

[back](../README.md)