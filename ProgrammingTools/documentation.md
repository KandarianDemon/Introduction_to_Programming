## Documentation

### Theory

To me, there are three levels of code documentation:

1. What does this line / piece of code do? -> Code Documentation
2. How can I use this code (function, class...)? -> API Documentation
3. How can I use this app? -> User Documentation

#### Code Documentation

And for each of these levels there are specific tools which can make it easier to write documentation. First, if you want to 'annotate' some part of your code, you can use the standard comments:

    cool code // This is a comment line

    /*
        This is a comment section
    */

Use this type of documentation to explain what some part of your code is doing and how it is doing it. It can also be helpful to add links here, if you adapted code you found on the web. It can save you tons of time when come over this part of your program the next time.

#### API Documentation

In many cases, you (and others using your code) might not be interested in the innards of your code but want to use it. For this, it is useful to document the interfaces of your classes, functions, ... For this type of documentation there are some nice tools which even allow you to automatically generate html or pdf pages! For Kotlin, we use [Dokka](https://kotlin.github.io/dokka/1.6.10/) and write documentation in the [KDoc](https://kotlinlang.org/docs/kotlin-doc.html) format. You can even use [MarkDown](https://www.markdownguide.org/getting-started/) in your documentation. Just as a note: This whole course is written in MarkDown!

    /**
        Describe your class / function
        
        @property[name] use KDoc syntax for defined features

    */

Here's a [Video](https://www.youtube.com/watch?v=GesMbOt5hIo) on KDoc and Dokka. 

#### User Documentation

For documentation on how to use your app, you can use GitHub. If you haven't pushed your app to GitHub, check [this section](./git.md). In the easiest case, just add a file named 'README.md' to the root directory of your app. This will be shown as starting page on GitHub.

If you have more extensive documentation, you might want to generate specific web pages. Again you can do this directly in GitHub using [GitHub Pages](https://docs.github.com/en/pages). You can write the documentation directly in your project. You can even use it to build your own web pages without any code. Actually, you are viewing this course right now on GitHub Pages!

### Actions

#### Dokka and KDoc

1. Install Dokka by adding `id("org.jetbrains.dokka") version "1.6.10"` to build.gradle(:app) plugins
2. Write a documentation for the Dice and Coin classes using the KDoc syntax. What do they do and how can I use them in my programs?
3. Generate the HTML documentation: Open the gradle pane (the elegant at the right-most column), click expand Tasks -> documentation, right click on dokkaHtml and click run. In your directory/file panel on the left side, switch to project mode. You'll find the generated annotation in app/build/dokka/html/index.html

#### GitHub Pages

Go to the 'Setting' tab. On the left, scroll down to 'Pages' and select. As source, use the Branch 'master' and as directory choose '/docs' (Hey, we are building extensive documentation, so we better put all this into an extra directory!). Choose a theme (how should your side look) and you're ready to go. On top of the page you see an URL, click it and be happy about your own documentation web side!

Te cool thing is, that you now can use all the Git / GitHub features in the development of your web side. That also means, that you can fork this course, make changes and send me a Pull request, and I can add your input directly to this course :-)

---

[back](../README.md)