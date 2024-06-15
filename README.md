Tic-Tac-Toe Game

Overview

This project is a fully functional Tic-Tac-Toe game developed using Java, leveraging the Swing and AWT libraries to create an intuitive graphical user interface (GUI). The game allows two players to play the classic Tic-Tac-Toe game with visual feedback and game state management.

Features

Graphical User Interface (GUI): Created using Java Swing components such as JFrame, JButton, and JLabel for a consistent and appealing interface.
Event-Driven Programming: Implemented with ActionListener to handle user interactions and update the game state in real-time.
Game Logic: Manages player turns, checks for winning conditions, and identifies draw scenarios.
Dynamic Feedback: Provides real-time feedback, indicating the current player's turn and highlighting the winning combination.
Reset Functionality: Includes a reset button to restart the game without closing the application.

Technology Stack

Java: The main programming language used for the application, offering platform independence and robust object-oriented features.
Swing: Part of Java Foundation Classes (JFC), used for building the GUI components.
AWT (Abstract Window Toolkit): Utilized for handling graphical and event-driven programming.

How to Run

Compile the Code:
javac Game.java
Run the Application:
java Game

Game Instructions

Start the Game: Launch the application to open the game window.
Make a Move: Player 1 starts by clicking on any of the nine buttons to place a cross (X). Player 2 follows by clicking on any empty button to place a circle (O).
Winning the Game: The game will automatically detect and highlight the winning combination if a player aligns three of their symbols in a row, column, or diagonal.
Reset the Game: Click the "RESET" button to start a new game.
