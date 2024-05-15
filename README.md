# CMSC132
A summary of projects completed in CMSC132 at the University of Maryland, College Park. Spring 2024. 

# Project 1: Tube Video Manager
Project Description: This project will allow you to review class definition, interfaces and testing. For this assignment, you will implement a video manager. You can add videos, create playlists, generate HTML for playlists, etc.

Interface Summary:
- TubeVideosManagerInt: Defines the functionality of the video manager.

Class Summary:
- Playlist: A playlist keeps track of titles and it has a name.
- TubeVideosManger: Implements the functionality of the videos manager.
- Video: A video has a title, url, durationInMinutes, and a genre.

Enum Summary:
- Genre

# Project 2: Web Page Generator
Project Description: This project allows you to practice inheritance concepts. For this project, you will develop a set of classes that will support the generation of HTML for web pages.

Interface Summary:
- Element: Represents an HTML element.

Class Summary: 

# Project 3: Clear Cell Game
Project Description: This project will allow you practice two-dimensional arrays, abstract classes, and test development. For this project, you will implement code for a game named clear cell game. The game's goal is to maximize the number of cleared cells in a colored board. 

Class Summary: 
- ClearCellGame: The class extends GameModel and implements the logic of the clear cell game.
- Game: This class represents the logic of a game where a board is updated on each step of the game animation.

Enum Summary: 
- Board Cell: This enumerated type represents a board cell.

# Project 4: Game Implementation
Assignment Description: In this project, you will use what you know about inheritance and inner classes to implement a game of your choosing.

Code Requirements:
- At least 3 different elements to your game in 3 classes
- 2 inner classes
- They must be in logical locations that take advantage of the inner class structure.
- 1 interface
- 1 anonymous class
- Must be in logical locations that take advantage of the anonymous class structure.
- 1 lambda expression
- Must have at least one element move using keyboard input
- Must handle collisions between elements
- Must rotate elements

Project Description: We made a version of the original Snake game. Using the arrowed keys, players can change the direction of the snake and earn points by eating apples. The apples randomly generate on the board. With every five points earned, a yellow apple will appear on the board; the yellow apple is worth two points. The game is over if the snake hits a wall or itself.

# Project 5: Linked Lists
Project Description: This project will allow you to practice linked lists and testing. For this project, you will implement a basic linked list and a sorted linked list.

Class Summary:
- BasicLinkedList<T>: This generic singly-linked list relies on a head (reference to the first element of the list) and tail (reference to the last element of the list).
- SortedLinkedList<T>: Implements a generic sorted list using a provided Comparator.

# Project 6: Online Test
Project Description: This project allows you to practice the design and implementation of object-oriented software systems. For this project, you will implement the data manager of an online test system. The system allows for the definition of exams with three possible kinds of questions: true and false, multiple choice, and fill-in-the-blanks questions. The system will grade submitted exams and generate some statistical information.

# Project 7: Binary Search Tree
Project Description: This project allows you practice binary search trees. For this project you will implement operations associated with a binary search tree. 

# Project 8: Orders Processor
Project Description: This project allows you to practice the design and implementation of concurrent systems. For this project, you will implement a program that processes files that represent purchase orders. The program can complete the processing by using a single thread or multiple threads.

# Project 9: Graphs
Project Description: This project allows you to practice implementation of graphs. For this project, you will implement Breadth-First Search (BFS) Traversal, Depth-First Search (DFS) Traversal, and Dijkstra's algorithm for shortest path computation.
