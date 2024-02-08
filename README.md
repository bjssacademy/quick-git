# A Quick Git Guide

Say you want to learn to program. You’re going to start with Python, Javascript, or another language (doesn’t matter which!) and start creating little programs or scripts. Think of Git as a way to create little waymarkers, or save points, at points in your code’s history. When you finish a specific feature, or finish a chapter, you can save the current version of your code. As you check-in your changes, you’ll create a log of your history.

This “history” is useful for several reasons: ​

• You can go back in time! Say you got everything working with a programming project, so you save your current progress to Git. Then you continue working, and ack—now it doesn’t work because there’s a bug! You can go back to the last “check-in” of your code and see what changed. ​

• You can create branches! Say your code is working smashingly and you deployed it live. Now you want to work on a new feature that’ll take quite a bit of time. Branching allows you to simultaneously create two different versions of your code that you can switch between. You can code your new feature on one branch, while keeping your current deployed version of code available in case you need to fix a bug. ​

• You can share this history with something like GitHub, an online hosting service for Git repositories, and be able to view your code and history online. We’ll cover this later in the guide! If that sounds confusing and too abstract, I hear you. It’s easier to understand in practice. Let’s start!

## Install Git

First, we need to install Git. It’s easy, I promise you, but for the sake of keeping this guide short, please head over to this very useful guide here for installation: ​

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

​All good?

## Get Started

```mkdir test​```

``cd test​``

Windows ```New-Item file.txt​```

Apple ```touch file.txt```

## Git Init

Git will only track the projects you tell it to track, so let’s tell Git to track this project folder with git init. 