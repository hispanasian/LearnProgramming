# 1.3 Hello World
###Goal
The purpose of this lesson is to get you to right your first program. 

##Lesson
###Create Your File
You'll notice that this branch is not as bare as our previous lessons. You should find a src/main/scala/ directory and a project/ directory with a file called build.properties in project/. You don't actually need to have a src/main/scala/ folder or a project/ folder, but it's nice to organize our files. Don't worry about the project/ directory for now and just focus on src/main/scala/.

Typically (in a scala project), scala code will be housed in the src/main/scala/ directory. You'll want to create a new file in src/main/scala/ called HelloWorld.scala. This is the file that will hold the code for your first program.

###Write Some Code
Now that your file has been created, you'll want to put something in it! I suggest you follow the Hello World [guide](http://www.scala-lang.org/documentation/getting-started.html) on the Scala page as we'll be implementing this program. 

Here's what the program does: It will print the string (essentially text) to a window. In this case, it will print "Hello, world!" to a window. Simple!

###Run The Program
Once you've actually written this code, you'll have two ways to run it:

1. Run the code through the IntelliJ IDE
2. Run the code through SBT (Scala Build Tool) 

####IntelliJ
If you're usinng an IDE, it's probably best to use it to build and run the code. To run the code in IntelliJ, you can:
1. Click the green "Play" button
2. shift + F10
2. alt + shift + F10

####SBT
I prefer to use SBT to build and run my projects, but it might not be the most comfortable thing for a beginner because you'll have to use the command line. SBT is a tool provided by the scala language that (as the name implies) helps with building your project. To learn more about SBT, you can check out the [documentation](http://www.scala-sbt.org/0.13/docs/index.html) or you can just check out a simple [hello world](http://www.scala-sbt.org/0.12.4/docs/Getting-Started/Hello.html) example.

To run HelloWorld in SBT, open up your terminal/command line and do the following:
```
cd /path/to/learnprogramming
sbt
run
```

To exit SBT, type:
```
exit
```

If you were successfull, you should see:
Hello, world!
printed to your screen. Congratulations! You've created your first program!

###Overview
You might be wondering now, "What did I just write? What is 'obeject'? What is 'main'? What is 'def'?" Don't worry. We'll get into all these things. I'll try to give you a brief introduction to some of these things that you just wrote, but don't get hung up on it. As you progress, you'll begin to understand programming a bit more and you'll start to grasp what all this stuff is.

####println
println is a command that the scala language provides to you. This is the command that prints "Hello, world!" to the window. Try playing with it. Change the text between the quotes and try re-reunning the program. You should see the text change to whatever **_argument_** you gave the println **_function_**. 

####def main
```scala
def main(args: Array[String]): Unit =
```
This is a **_method_** declaration for the _HelloWorld_ **_object_**. It says that HelloWorld will support a **_method_** called _main_ which takes in a signle **_argument_** called **_args_** which is an **_Array_** of type **_String_**. This method will return a **_Unit_** when executed. I know that was a mouthful. I just want you to get exposed to some of the terminology and how you might read this.

###Solution
If you have trouble with this lesson, you can check the solution:
```
git checkout upstream solution/1.3_hello_world
```

###Nex Lesson
Now you're ready to move on to the next lesson where we'll get your computer set up to start programming! First, checkout the next lesson:
```
git checkout upstream lesson/1.2_setup_environment
```
Now head on over to the next lesson: [Setup Environment](https://github.com/hispanasian/LearnProgramming/tree/lesson/1.2_setup_environment)
