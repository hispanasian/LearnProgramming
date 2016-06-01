#2.1 Intro to Programming
###Goal

The purpose of this section is to get you acquainted with some basic programming concepts. The lesson will be heavily based off of this [Scala Tutorial](http://scalatutorials.com/tour/#). I highly recommend it so you can get a basic understanding of some key programming concepts.

##Lesson
###Scala Interpreter
One of the cool things about the java programming language is that it comes with an interpreter. Your typical high level language (java and c++) does not have an interpreter as part of the language. What is an interpreter? Well, open up your CLI and type:
```
scala
```
That's it. You are now in the scala interpreter. In there, you can type in commands as if you were writing a programming and the interpreter will execute those commands.

For example, try
```
var x = 5
```
The interpreter will respond with
```
x:Int = 5
```
The interpreter just took your input and recognizes that you initialized a variable __x__ which is of type __int__ and has a value of __5__. You can use the scala interpreter for many of the excercises in this lesson. It's also a neat way to make a quick little script that you just need to run once. To quit the scala interpreter, type
```
:q
```
###Excercises
You should find some files in src/main/scala. Each file will start with a number (starting from 1) and continue, along with an appropriate name for each.

Each file will explain some concept and tell you what to do. For example, you should start with:
src/main/scala/1 Comments

This file will explain some things and then tell you which file to go to the next file:

Typically (in a scala project), scala code will be housed in the src/main/scala/ directory. You'll want to open the file src/main/scala/HelloWorld.scala. This is the file that will hold the code for your first program.

###Next Lesson
Now you're ready to move on to the next lesson where we'll get your computer set up to start programming! First, checkout the next lesson:
```
git fetch upstream lesson/1.2_setup_environment
git checkout -b lesson/1.2_setup_environment upstream/lesson/1.2_setup_environment
```
Now head on over to the next lesson: [Setup Environment](https://github.com/hispanasian/LearnProgramming/tree/lesson/1.2_setup_environment)
