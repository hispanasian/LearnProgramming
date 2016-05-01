# 1.1 Learning Git
###Goal
The purpose of this lesson is to teach you how to use git. Git is a version control system. If you want to learn more about git, you can read up [here](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).

##Lesson
###Learn Git
There are plenty of resources out there to learn git. In fact, github has a [list](https://help.github.com/articles/good-resources-for-learning-git-and-github/) of resources. Here's a list of one's I recommend:
-[git's tutorial](https://try.github.io/levels/1/challenges/1) (I recommend this one to start)
-[cool git game on github](https://github.com/git-game/git-game)
-[interactive tutorial](http://pcottle.github.io/learnGitBranching/)
-[codecademy](https://www.codecademy.com/learn/learn-git)

Don't feel overwhelemd with all the resources. The point is not to make you a git expert, but to get you to the point where you can start using this repository. I suggest you just go through the first resource and then continue with this lesson.

###Fork the LearnProgramming Repository
First thing you'll want to do is fork this repository. (Forking)[https://help.github.com/articles/fork-a-repo/] is a github feature that allows for users to make a copy of an existing repository but treat it as their own repository. This way, you can work on the repository and make changes to it without interfering with others.

You can fork this repository by going to [LearnProgramming](https://github.com/hispanasian/LearnProgramming) and clicking the fork button. The fork button can be found on the top right side of the page.

###Clone the Forked Repository
Now it's time to put your new found git skills to the test. First, you'll have to [install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). For windows, you'll want to add git to the PATH. I also suggest you use the git bash tool instead of command line for using git.

Now clone this repsository. There are multiple ways you can do this. You can either [use IntelliJ](https://www.jetbrains.com/help/idea/2016.1/cloning-a-repository-from-github.html?origin=old_help) or you can use a command line tool. This project will use the command line when walking through git.

The command line (Windows) and terminal (OS X/Linux) have different commands, there are some similar ones. Thankfully, they share similar navigation commands. Now, open up your CLI (command line interface) and do the following commands
```
cd '/path/to/where/you/want/to/put/the/project'
git clone https://github.com/YOUR_USERNAME/LearnProgramming.git
cd LearnProgramming
git remote add upstream https://github.com/hispanasian/LearnProgramming.git
```
So what exactly did you just do? You've put just downloaded your forked repository of LearnCoding onto you computer to /path/to/where/you/want/to/put/the/project/LearnProgramming. You then added the original repository for LearnProgramming as a remote to your local git and called it *upstream*. 
