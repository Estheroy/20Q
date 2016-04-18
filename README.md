# 20Q
This Java Project is a simple game similar to 20Q implemented by a binary tree. 
In the game 20 questions, the player begins by thinking of an object. The computer's goal is to successfully guess what that object is. This program will ask the player a set of 20 questions (maybe more or less), attempting to narrow down the list of possible results until it finally thinks it knows the answer. It will then present the result to the player. If the computer successfully guesses the object it wins, otherwise it loses. Note that the number of questions is not always 20 and it will depends on the existing game tree.


### Usage
The game can be run either by loading an existing 20 questions tree from a file (see file format in tree.txt), or by starting with a simple default tree with 4 questions. If the program loses, i.e, make a wrong guess, it will ask user to enter the correct answer to augment the binary game tree.

a) Run with the default 4-question tree

>- ***java  -jar TwentyQuestions.jar***

b) Run by loading an existing game tree

>- ***java -jar TwentyQuestions.jar filename***
