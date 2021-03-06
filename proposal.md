# X-Team 120  Animal Organizer Proposal

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

You are the owner of a pet store. This program will help you keep track of the animals coming in and out, and the
care necessary to maintain these animals, including feeding and hygiene.

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

    * Animal organizer.


2. Output: Describe the output your program will produce.  Include and example format of the output produced.

    * It will produce a text menu, and take user input to show the animals in each section of the store, and their necessary care at that time.


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

    * Type of pet added
    * Sale of pet, time sold
    * If care is needed

```
------------------
| PET STORE NAME |
------------------
1. Care Needed
  -----------
  Dog1 - feed
  Cat2 - clean
  Snake3 - give medicine
  -----------
2. Current pets
3. Sold pets

Press the number to view that list:__

```

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

```json

{
    "dog1": {
        "type": "dog",
        "timeSold": 1540774572,
        "careNeeded": false
    }
}

```

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

    * The user interface would be a text menu, where the user can view lists of current animals in the store, if care is needed for that pet, and a list of sold pets for record keeping.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

    * We need to break everything down into the store, each animal type in the store, a management system to keep track of which animal needs care.


Name each interface or class and briefly describe its function or purpose.

    Animal class -> with specific pet types (bird, dog, cat, rodent, reptile) as classes that will be inherited  

    CareQueue class -> where we will store the information of the care that is needed for each animal

    Store Class -> will be the main class where everything is implemented, including keeping track of sales and adding new animals

## Edit and Submit this file and any figures referenced by this document.
