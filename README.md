## An introductory course to programming (not only) for Biologists

### Overview

#### Goal

In this course you will learn how to program simple android apps in Kotlin. In the process, you will be introduced to the basics of imperative and Object-Oriented Programming. You will use industry standard software development tools to produce reliable, readable and extensible code.

#### Why might this course be interesting for you?

Did you ever want to write your own Android App? Did you want to learn coding? Did you want to give your CV a special edge? Then this course might be interesting for you.

In this course you will learn the programming language [Kotlin](https://kotlinlang.org/) and use it to program your own Android Apps. In 2019, Google announced that Android development is [Kotlin first](https://android-developers.googleblog.com/2019/12/androids-commitment-to-kotlin.html). In 2020, 70% of the top 1000 apps on the Play Store were written in Kotlin. But there is more. You can program your own web services (backend) and web clients (frontend) in Kotlin. Additionally, you can even use Kotlin for data science! So you can be sure that you are learning a language wich is relevant today and will stay relevant in the future. This [summary Video](https://www.youtube.com/watch?v=CQlBQ5tfbHE&list=PLlFc5cFwUnmzT4cgLOGJYGnY6j0W2xoFA&index=2) gives you an impression which universities use Kotlin in education and why they do so.

#### Course Structure

This course is structured as [inverted classroom](https://en.wikipedia.org/wiki/Flipped_classroom). That means that within the week you will work self-paced and solve programming tasks. You will learn about the theoretical background of the weeks assignment by written information as well as by videos. Every thursday, we will meet and talk about problems, ideas and challenges you run into. With this format, you will not only learn the needed programming skills, but also how to gather information, teach and improve by yourself. Especially in a fast developing field like programming this is a fundamental skill. As it can be quite frustrating if you run into a problem and are stuck (own experience here), I also created a Discord channel for this course which will allow you to interact with other students.

In the first eight topics, you will learn the necessary basic skills to write an Android App. Here, we will use exercise from the [Atomic Kotlin](https://www.atomickotlin.com/) book. You will solve this tasks directly in the [Integrated Development Environment](https://en.wikipedia.org/wiki/Integrated_development_environment) you will also use for coding your Apps. In parallel, you will apply the new concepts to program [your first App](https://github.com/Joerg-Schultz/DiceApp) and learn about basic concepts of Android programming.

In the second part, which will be about four weeks, you will apply your knowledge. You will pitch the idea of your own App to the course, and we will discuss which additional features are needed. Then you will program it - either on your own or as a small dev-team. We will meet again every week and each developer / team can present new features they learned. And of course discuss problems they ran into.

#### Course Content

Kotlin
- Variables (val vs var)
- data types incl. nullability
- classes (properties, member functions, default values)
- functions
- control structures
- Collections (list, mutability)

Android programming
- jetpack navigation component / Fragments
- ModelViewViewmodel Design
- XML based Layout (might change to compose)
- UI Elements

Programming Tools
- Integrated Development Environment
- Debugging
- Version control (Git, GitHub)
- Documentation
- Testing

### Teaching Units

#### 1. Setup and Variables

1. [Setup](./Setup/setup.md): Where you will install the needed environment (IDE, Exercises)
2. [Hello World](./HelloWorld/helloworld.md): Where you will run yor first Kotlin program.
3. [Variables](./VariablesAndDataTypes/variables.md): Where you will learn about two different types of variables in Kotlin.
4. [Data Types](./VariablesAndDataTypes/datatypes.md): Where you store different things in variables.
5. [Your First Android Program](./DiceApp/emptyproject.md): Where you will generate your first Android program!
6. And change the displayed text

#### 2. Functions (and Nullability?)
7. Nullability (or leave this out for now?)
8. [Functions](./Functions/functions.md): Where you will give parts of your code a name to execute from everywhere in your code. 
10. Android Button setzt Variable plus text input field (for the fun of it)

#### 3. Control statements
10. [if Statements (and Booleans)](./ControlStatements/ifstatements.md): Where you will learn how to test for conditions and then conditionally execute code.
11. [while](./ControlStatements/while.md): Where you will find a first way to run the same code multiple time.
12. [for and ranges](./ControlStatements/for.md): Where you will execute a code block for a given number of times.
14. Android: (i) Count how many times you pressed a button (ii) generate random number and display it

#### 4. Collections
15. Exceptions (for capture {} and to know what they are)
16. [Lists](./Collections/lists.md): Where you will work with a container that can hold multiple things
17. [Sets](./Collections/sets.md): Where you will generate Containers which contain just unique elements.
18. [Maps](./Collections/maps.md): Where you will learn to build a key-value stat structure.
19. [Summary](./Collections/wrap_up.md): Just a summary of all these Collections plus some additional cool functions to work with them.
20. Android: Generate a list of the random values and display this growing list in a text field.

#### 5. Classes

21. [Classes](./Classes/classes.md): Where you will have first contact with the basic unit of object-oriented programming - the class.
22. [Inheritance](./Classes/inheritance.md): Where you will learn about Rodents, Rats and Mice and why this is related to Kotlin.
23. [Visibility](./Classes/visibility.md): Where you will hide variables and functions from outside observers.
24. Android generate a dice class. Generate a Coin class, which is a two-sided dice. Generate a parent class dice and inherit from it to generate a 'standard' dice and a coin-dice.

#### 6. MVVM


#### 7. Navigation


#### 8. git+github, gitpages, Dokka, Testing :o

**Git and GitHub**
Just view the [Git for Android Developers Series](https://www.youtube.com/watch?v=zqo08bQXU4Q&list=PLQkwcJG4YTCQTEk4J4btiOJBV0PhKjJVS) and get your own version of our DiceApp up to GitHub.

**Dokka**

**Testing**


#### Program your own App!

#### Final Unit

Deploy your App to the Play Store!
