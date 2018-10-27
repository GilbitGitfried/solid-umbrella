# X-Team 101 Gift Planner

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

Problem: Each month, you have a limited budget to get each of your friends a birthday gift.
You want to get some friends a better gift than others.

Based on information about all of your friends and their birthdays, you want to know how much to spend
on each friend, based on how good of a gift you want to get them.

A "Person" class can contain the neccessary information about your friends, i.e.
Name, Birthday, a "friendship" rank of how much you like them, and a budget for their gift (this field is generated later).
A hash table can be used to store instances of "Person".

The main class runs a text menu for:

1.) Adding a new friend

2.) Removing a friend

3.) Modifying a friend's information

4.) Generating a gift-budget plan

5.) Saving the stored friends to a file

6.) Loading friends from a file

When generating a gift-plan, you will specify a month and input a monthly budget. The program computes how much you can spend on each friend based on
the ranking of how much you like them. A priority queue is created, and instances of "Person" are added. The priority queue then prints elements in order
of "friendship rank", displaying the individual's name, their birthday, and how much you can spend on their gift.

## Questions to answer for Exercise #2

1. Name: 

Gift Planner


2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The output will produce a list of people who have birthdays in the specified month, ranked by how good of a friend they are, with a specified amount for how much you can spend on their gift.

Example:
Ross Skelly - 1/16/1994 - $54
June Tabithat - 1/4/1993 - $50
Edgar Poe - 1/19/1890 - $12




3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The input data is the data needed to construct an instance of "Person"

Example:

Input Name:
"Ross Skelly"

Input Birth month:
"January"

Input Day of birth:
"16"

Input Year of birth:
"1994"

Input on a scale of 1-10, how good of a friend this person is:
"2"



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

The UI for this program will be a text menu, run from the main class with options as follows:

1.) Adding a new friend

2.) Removing a friend

3.) Modifying a friend's information

4.) Generating a gift-budget plan

5.) Saving the stored friends to a file

6.) Loading friends from a file



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

We will need interfaces and implementations for a priority queue and a hash table. Another class to create instances of individuals will also be required. The main class will handle user interface/input and saving/loading information. The main class will also handle calls to helper classes when appropriate.



Name each interface or class and briefly describe its function or purpose.
Priority queue interface/class - ADT and implementation of a priority queue, used to organize the return order of indivduals
Hash table interface/class - ADT and implementation of a hash table to store instances of Person class
Person class - Used to construct and store data of individuals
Main class - handle running of program and user interface and saving/loading files


## Edit and Submit this file and any figures referenced by this document.

