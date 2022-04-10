## Documentation

### Theory

Hey, I wrote this code! I know what I did! Why should I waste my time writing boring documentation?

https://kotlinlang.org/docs/kotlin-doc.html#module-and-package-documentation

https://kotlin.github.io/dokka/1.6.10/

add `id("org.jetbrains.dokka") version "1.6.10"` to build.gradle(:app) plugins

Then write your documentation in KDoc style. If you want to generate an html documentation fpr your project, open the gradle pane (the elegant at the right-most column), click expand Tasks -> documentation, right click on dokkaHtml and click run. In your directory/file panel on the left side, switch to project mode. You'll find the generated annotation in app/build/dokka/html/index.html

[Video](https://www.youtube.com/watch?v=GesMbOt5hIo) on KDoc and Dokka.

### Actions

Write a KDoc documentation for your App and extract it into html.

---

[back](../README.md)