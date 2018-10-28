# X-Team 123 Calendar Lite Proposal

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
It is often difficult to keep track of all of events in a day and their details, especially for students. So we need a special calendar to manage all of our events including lectures, exams, assignments in a simpler way. The Calendar Lite can help resolve this problem. Using Calendar Lite, the users can easily manage all of their events in a short time.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)
* Calendar Lite


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
* The events and tasks in a day.

* 10/26/2018 Friday
* 1
Computer Science 400
Time: 8:50 - 9: 40
(Bring Laptop)
* 2
Computer Science 240
Time: 9:55 - 10:45
(Bring the handout from last lecture)


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
Input: event and task details
* 1
Event: Computer Science 400
Time: 8:50 - 9: 40
Note: ---------------


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
* [figure 1](https://github.com/REEEYZ/user-interface/blob/master/xteam%20exercise%202b%20ui.jpg)
* description:
In figure1, there is a bar on the top which can serve as a navigator. Users can use it to navigate to the week they want to check. The main calendar is in the center of the screen. The users can check their events there. Every event will be put in teh correct date and time. There is also a check box on top of each event. The users can click on it to mark it as completed or cancelled. If the users double click on a event, there will be a small window poping up to show the details of that event. The users can also edit the details there.



5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
* Event class - Object to store time, name, details, and whether event is completed. It is the most basic unit in our program. It is used to store data.
* Calendar class - Custom data structure to store events. Data structure is an array of linkedList<Event> which stores all of the event. The array consists of 31 objects each representing a day. The linkedlist<Event> stores all the events on that day.
* CalendarGUI - Contains the user interface, it will create the user interface and control its interation with the user.
* Main - Class used to run the program.
* Test - Class to test the funcitionality.


## Edit and Submit this file and any figures referenced by this document.

