# X-Team 45 Project Proposal- Chore Assigner

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

* Our team has decided to solve the problem of roommates not completing their chores. Often times chores go undone in an apartment or house because no one wants to take it upon themselves to clean the kitchen or vaccuum the family room. Or, a roommate will say they will clean something and as the weeks go by, it remains dirty. This is a very prevelant issue inside of the college communities all across the world, and we would like to resolve this once and for all.

Describe at a high level a program that could solve that problem.

* Our program will make explicityly assigning chores to roommates easier, quicker, and more efficient. Each roommate will be able to see their list of chores, each of their roommates' list of chores, and the due date for each of their chores. If one roommate has not completed a chore, you will be able to send a push notification (email) to the roommate to remind them to complete their assigned chore. After somebody completes their chore, they can check off that chore on their list. If the chore was completed unsatisfactorily, the roommates will be able to veto that completion and the person responsible for that chore will have to complete it to a higher standard. After the week ends, everyone's completed chores will be unassigned and another chore draft will commence.
* Data Structure - 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
: Chore Assigner 


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
* List of chores assigned to each person with the date/time expected it to be complete
* Push notifications
* Rating of a completed chore job


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
* House members (names and amount of house members)
* Chores
* Weights on Chores (i.e., cleaning the bathroom does not hold the same weights as wiping the counter)
* Date/time expected it to complete
* Draft system to choose chores (think fantasy football draft but for chores)


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
![ChoreAssignerDiagram](https://github.com/34conman/musical-octo-umbrella/blob/master/ChoreAssignerDiagram.jpg?raw=true)


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.



Name each interface or class and briefly describe its function or purpose.
* Resident Class: inializes each resident with a name and chore rating, which gets updated each week by input from other residents
* Chores Class: Initializes a chore with a name, weight and expected time for completion
* Notification Interface: Outputs specified message to residents
* Chore Assignment Interface: Uses an algorithm to assign chores to the residents
* Fantasy Football Assignment: Implements Chore Assignment Interface and allows the residents to choose their chores in a fantasy football-like draft
* Random Assignment: Implements Chore Assignment Interface and randomly assigns chores to the residents
* Main Class: Instantiates "households" which are the ArrayLists
* JUnit test Classes: Tests program

## Edit and Submit this file and any figures referenced by this document.

