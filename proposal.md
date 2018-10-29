# X-Team 111 Project Proposal: Money Tree

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

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
Money Tree


2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The user inputs a category of their expenditures they would like to look at. The program produces a pie graph of what the user spent in the last month. For instance if the category is food, each slice of the pie graph is an individual foot item the user has purchased. In addition, the user has the option to be shown a line graph of their purchases over time.  



3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
We need data for each expenditure, which can be obtained either by asking the users to manually put in the transaction, or by pulling the data through the API of the bank.

- Example: 
- Payee: Wiscard
- Amount: $5000
- Category: Food
- Date: 10/29/2017




4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
Our home page would consist of a picture in the middle of a tree (because of our project name), and there would also be buttons for logging in and signing up. There will be links that explain how the program keeps track and categorizes your spending, another link for its uses, and an about us link on the homepage. Once signed in, the user will be welcomed with a brief update on their spending since the last time they logged in, and tracking graphs on how their spending has changed. We plan on integrating inputs from one’s bank, and manual inputs, so if the user uses cash to buy something, they could manually track it. We would also delete duplicate expenditure if our algorithm found a resemblance between price and categorization by prompting the user and asking if it’s a duplicate item. 



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Name each interface or class and briefly describe its function or purpose.

Main(); To run the program to test if it works, call the methods in order that they’re needed. 
AVL tree interface and subsequent methods, to provide the scaffolding for the AVL tree. 
Userinput(); method. To read user input and text files coming in, and check that they’re appropriate. 
delete/clear expenditure method. To delete the inputs from the tree/array. Has the option for the user to delete select data instead of all the data. 
Junit tests. To test for failure and check if errors are thrown correctly. 
Print(); print out results in text format. 
PrintGraph(); print out the graph based on text 



## Edit and Submit this file and any figures referenced by this document.

