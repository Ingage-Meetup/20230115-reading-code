# Code Reading Excercise
As an industry we generally focus our technical growth on learning new lanugages, frameworks, and writing greenfield code.
Too often we ignore the skills it takes to read an understand existing codebases. This exercise is focused on these skillz.

## Useful links
* [mystery_application.bas](mystery_application.bas) Source Code for the exercise
* [Vintage Basic User Guide ](http://www.vintage-basic.net/downloads/Vintage_BASIC_Users_Guide.html)
* [Vintage Basic Installation Files](http://www.vintage-basic.net/download.html)

If you prefer to use a browser based BASIC Interperter
* [JS Basic](https://troypress.com/wp-content/uploads/user/js-basic/index.html)
* [Online Basic Compiler](https://www.tutorialspoint.com/execute_cbasic_online.php)

## The Situation
Your boss has just walked into you team room looking frantic. An application used by one of the big wigs is no longer running. The team that used to support it has long ago been disbanded, and as far as anyone can remember the members have long since retired. They have not found any relevant information in JIRA, Confluence, or any old requirements or architecture document.

## The Challenge 
### Part 1 - Code Analysis
As a group read through the code printouts and try to make sense of what the application does. Feel free to make any notes, draw diagrams, read the Vintage Basic manual, or even markup the source code with your editor. 

**The only constrain is to not run the application YET!**

### Part 2 - The Running App
Now you can run the mystery application. Does it behave exactly like you expected from just reading the code? Can you glean any other insights playing with the application that may have been hard to see by just reviewing the source.

Feel free to make temporary changes to the code to understand it better. Are you able to make improvements (i.e. refactor) to make it more understandable, while still having confidence that it works the same as the unmodified code?

### Part 3 - The Rewrite
Create either a direct port of the existing code, or rewrite it entirely. Please use a modern language so that it can be more easily maintained and supported for the foreseeable future. Perserve as much of the functionality as possbile. 

For bonus points keep track of possible improvements that the rewrite could enable so we can discuss with the Product Owner.

# C3ProjectTemplate

See solutions in different languages in the "Templates" directory. Once you decide which language you'd like to use,
simply open that directory in your favorite IDE, and you should be able to run the included unit tests "out of the box".

The recommended IDEs are as follows, but feel free to use whatever IDE you are comfortable with.

-   [C#](Templates/C#) - [Microsoft Visual Studio](https://visualstudio.microsoft.com/vs/community/)
-   [Java](Templates/Java) - [IntelliJ Idea](https://www.jetbrains.com/idea/download) (Community Edition is fine)
-   [JavaScript](Templates/JavaScript) - [Microsoft Visual Studio Code](https://code.visualstudio.com/)
-   [Kotlin](Templates/Kotlin) - [IntelliJ Idea](https://www.jetbrains.com/idea/download) (Community Edition is fine)
-   [TypeScript](Templates/TypeScript) - [Microsoft Visual Studio Code](https://code.visualstudio.com/)
