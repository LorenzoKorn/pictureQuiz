# pictureQuiz
A simple app that checks the users input

## Questions
### What does the abbreviation ART stands for?
Android Runtime (compiler)

### What is Android Jetpack?  
Android Jetpack is a set of libraries, tools and architectural guidance to help make it quick and easy to build great Android apps. It provides common infrastructure code so you can focus on what makes your app unique

### Describe the difference between the fixed, wrap_content and match_constraint setting of the constraint layout?
#### fixed
exact position and size of the element
#### match_constraint
Gives the element the size including the constraints, which makes the element slightly bigger.
#### wrap_content
Makes the element as big as the content inside.

### What does the abbreviation DP stand for and why do we need them?
density-independent pixels
DP doesn't get resized when the user changes it's size preference like SP (scale-independent pixels) does. This makes the element have a fixed size on all devices.

### What is the purpose of the string.xml file?
To keep your strings separate from your activity xml file. This make it easier to, for example, have multiple languages in your app, without having multiple hard coded screens.

### Why is the layout in Android specified by .xml files?  Why not just have the layout in the code (Kotlin or Java)?
It's more clear and it followes the the separation of concerns rule

### In the level 1 example the following code was used: btnConfirm.setOnClickListener What is a listener and what is the underlying design pattern?
A listeren is an event that gets triggered when some activity is fired. Iin this example: the listener 'listens' to a click on the button, when that happens, it will execute the code. 
the design pattern is the observer pattern
