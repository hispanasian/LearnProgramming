# 1.2 Setup Environment
###Goal
The purpose of this lesson is to get your environment (your computer) ready to start programming. To do this, we'll need to download a couple programs. Don't worry though, they're all free.

##Lesson
###Get the Java JDK
First things first, we'll want to [download](http://www.oracle.com/technetwork/java/javase/downloads/index.html) and install the Java JDK (Java Development Kit). From the linked page, click on the "download" button located under "JDK" and then simply download the JDK that pertains to your operating system. You can just select one of the options from the first list. 

Installing the Java JDK will, among other things, install the java compiler on your computer so you can start writing java code. But wait, wasn't this project going to use Scala? Don't worry, we'll be using Scala. It's just that we need java to be able to use Scala. If you're interested as to why that is, it's because Scala compiles to Java byte code. This allows Scala to make use of the Java JVM. The Java JVM is a program that executes Java byte code on your computer. If this just made you more confused, don't worry. This isn't critical stuff. 

###Get Scala
Now it's time to [download](http://www.scala-lang.org/download/) and install Scala. You can ignore the download for "Lightbend Activator" unless you're interested in it.

###Get IntelliJ
Finally, you'll want to [download](https://www.jetbrains.com/idea/) and install IntelliJ. This will be our IDE for Scala. During the install process, make sure you download the Scala plugin. 

-Once you've installed IntelliJ, you'll want to open up this project. To do that, simply open this project from InelliJ. You may need to tell IntelliJ where to find the JDK and Scala. use [this](http://nanxiao.me/en/getting-started-with-scala-in-intellij-idea-14-1/) guide to help you. You can just create a new project if that's easiest for you.

###Nex Lesson
Now you're ready to move on to the next lesson where we'll create your first program! First, checkout the next lesson:
```
git fetch upstream lesson/1.3_hello_world
git checkout -b lesson/1.3_hello_world upstream/lesson/1.3_hello_world
```
Now head on over to the next lesson: [Hello World](https://github.com/hispanasian/LearnProgramming/tree/lesson/1.3_hello_world)
