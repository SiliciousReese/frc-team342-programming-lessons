# Python Tutorial

Daniel Darnell

20190922, updated 20190922

Version 0.1

My attempt to write more focused programming lessons

# Overview

Computer science is a broad topic, and getting started with any part of it can
be overwhelming. I am going to use Python programming as a jumping off point to
get started with all the basics of computer science as a whole. This tutorial
will mostly focus on the language, but I will try to tie in outside topics for
the reader to understand where this fits in the scheme of things, and to allow
the reader to do further research.

I will be using the official python tutorial by the python development team.
The tutorial very well written on its own, but I wanted my own version to allow
more focused teaching.

## Getting Started

First read the intro in chapter 1 to get a basic understanding. Chapter 2 goes
into setting up the programming environment and using the interpreter. Chapter
3 is where the programming starts.

The tutorial starts one line of code at a time. It introduces basic
expressions, such as arithmetic, assignment, string and list handling and
comparisons.

Chapter 4 starts with a more focused approach into control structures. This is
where the actual planning and logic behind writing code starts to come in to
play. Before going into it, make sure you feel comfortable with the previous
topics.

## Control Structures

The control structures we will go over are if, while, for, and defining functions.

The simplest form of program control is an if statement. It is fairly self
explanatory.

    experience = int(input('On a scale of 1 to 10, How 
                             much programming experience 
                             do you have?'))

    if experience > 7:
        print('Very Experienced')
    elif experience > 2 and experience <= 7:
        print('Some Experience')
    elif experience > 0:
        print('A little experience')
    else:
        print('No experience')

This allows the program flow to "branch", ie instead of following one single
path with no choices like cooking recipe the code can now do different things
depending on the user input. This is the basic concept of flow and control
structures.

While if statements are very simple, they only allow a finite number of
choices. What if you wanted the program above to repeat many times, allowing
multiple people to type in their experience? When we want to repeat code over
again, we use loops. The simplest loop is a while loop. It simply repeats code
until a condition is met.

Typically you want to repeat a loop a specific number of times. The for loop in
python is similar to the while loop, but specifies a range to iterate over
instead of just a basic condition. For loops are much more common in
programming, usually you want the loop to just run a certain number of time.

# TODO

Write a review / study guide / test before starting control structures.

Add links
