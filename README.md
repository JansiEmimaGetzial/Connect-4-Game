# Connect 4 Java Game

## Overview

Welcome to the Connect 4 Java game repository! This project allows two users to engage in a classic Connect 4 game where one is assigned the color Green, and the other plays with Blue. The objective is to align the chosen color four times consecutively, either horizontally, vertically, or diagonally, to secure victory.

## Technologies Used

- Java
- Swing packs (JFrame and JPanel)
- MouseListener and MouseEvent for user interactions

## Project Structure

- *Main.java*: Entry point of the application.
- *DrawGrid.java*: Class responsible for drawing the game grid and managing the game process.
- *CheckForWinner.java*: Contains the logic to determine the winner by checking all possible diagonals.

## Implementation Details

- *User Interaction*: Utilized MouseListener and MouseEvent for handling mouse clicks, entry, and exit events.
- *Grid Design*: Implemented a class named DrawGrid to facilitate grid creation and management.
- *Paint Component*: Leveraged void paintComponent() to color the grid and enhance the visual experience.
- *Winning Check*: Incorporated the checkForWinner() method to assess the game board for winning alignments.

## How to Play

1. Clone the repository.
2. Compile and run Main.java.
3. Enjoy a Connect 4 game with a friend!

Feel free to explore the code, provide feedback, or contribute to make this Connect 4 Java game even more exciting. Happy gaming! 🎮
