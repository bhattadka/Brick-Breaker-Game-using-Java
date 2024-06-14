# Brick-Breaker-Game-using-Java

Welcome to the Brick Breaker Game repository! This project is a classic brick-breaker game implemented in Java. The game includes features like  game won/lost conditions , scoreboard and a dynamic interface.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [File Descriptions](#file-descriptions)
- [Technologies Used](#technologies-used)


## Introduction

The Brick Breaker Game is a popular arcade game where the player controls a paddle to bounce a ball and break bricks. This implementation includes a graphical user interface and tracks the game state to determine when the game is won or lost. It also records player's score.

## Features

- Game won and game lost conditions
- Dynamic interface with graphical elements
- Responsive controls

## File Descriptions

### `Main.java`

This is the main class file that initializes the game. It sets up the game window and starts the game loop.

- **Responsibilities:**
  - Initialize the game window.
  - Start the game loop.

### `MapGenerator.java`

This class file generates the map of bricks for each level. It dynamically creates the arrangement of bricks that the player needs to break.

- **Responsibilities:**
  - Generate the layout of bricks.
  - Manage the state of each brick (broken or intact).

### `GamePlay.java`

This class file handles the core gameplay mechanics, including player input, ball movement, collision detection, and game state updates.

- **Responsibilities:**
  - Handle player input and paddle movement.
  - Control ball movement and detect collisions with bricks, walls, and the paddle.
  - Update the game state and check for win/loss conditions.


####  Images

- `GameInterface.png`: Screenshot of the main game interface.
- `GameWon.png`: Image displayed when the game is won.
- `GameLost.png`: Image displayed when the game is lost.

## Technologies Used

- **Java:** The programming language used to develop the game.
- **Swing:** Java's GUI widget toolkit used for creating the graphical user interface.
