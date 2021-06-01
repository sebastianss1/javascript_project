# Sebastian's Type Manipulator 

## Background

I have always been interested in graphic design and typefaces. Sebastian's Type Manipulator is a study of manipulating typefaces by using Javascript. This project studies the movement, color, size and scale of words. 

There will be many ways to manipulate text, outlined in the Functionality & MVP and Bonus Features sections.

## Functionality & MVP
With Sebastian's Type Manipulator, users will be able to:

* Type any words or phrases of their own (limit 100 characters)
* Toggle between multiple colors 
* Toggle movement and rotation of words
* Select different shapes a word can create i.e. cubes or cylinders 
* Reset all changes

In addition, this project will include:

* An About modal describing how to use the Type Manipulator 
* A production README

## Wireframes
This app will consist of a single screen with a text input area and some levers to change toggle between all settings listed in the Functionality and MVP section. The app will also have nav links to the Github, my LinkedIn, and the About modal. 

wireframes

Architecture and Technologies
NB: one of the main things you should be researching and deciding upon while you write this proposal is what technologies you plan to use. Identify and create a plan of attack for the major technical challenges in your project.

This project will be implemented with the following technologies:

JavaScript for game logic,
Foo.js with HTML5 Baz for effects rendering,
Browserify to bundle js files.
In addition to the entry file, there will be three scripts involved in this project:

board.js: this script will handle the logic for creating and updating the necessary Foo.js elements and rendering them to the DOM.

automata.js: this script will handle the logic behind the scenes. An Automata object will hold a type (hexagon, triangle, or square) and a 2D array of Cells. It will be responsible for doing neighbor checks for each Cell upon iteration and updating the Cell array appropriately.

cell.js: this lightweight script will house the constructor and update functions for the Cell objects. Each Cell will contain a type (hexagon, triangle, or square) and an aliveState (true or false).

## Implementation Timeline
Day 1: Research how I will be implimenting this project. Most likely Vanilla JS. 
Setup all necessary Node modules, including getting webpack up and running. Write a basic entry file and the bare bones of all 3 scripts outlined above. 

Day 2: 
Day 3: 
Day 4: 