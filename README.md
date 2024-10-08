# Arkanoid Game in Java

## Overview

This is a Java-based implementation of the classic Arkanoid game. The game features a paddle controlled by the player and a ball that bounces off the paddle and bricks. The goal is to break all the bricks without letting the ball touch the ground.

## Features

- **Paddle Movement**: Use keyboard arrows to control the paddle's movement.
- **Ball Physics**: Realistic ball physics for bouncing off the paddle and bricks.
- **Brick Levels**: Different levels of bricks that require a hit to break.
- **Score Tracking**: Keep track of your score as you break bricks and complete levels.
- **Game States**: Start, Pause, and End screens for better game control.

## Compilation and Execution

### Install Apache Ant

To compile and run this project, you need Apache Ant installed:

1. **Download and Extract Apache Ant**:
   - Download from the [Apache Ant website](https://ant.apache.org/bindownload.cgi).
   - Extract it to a directory (e.g., `C:\apache-ant-1.10.13`).

2. **Set Up Environment Variables**:
   - Set `ANT_HOME` to the Ant directory (e.g., `C:\apache-ant-1.10.13`).
   - Add `%ANT_HOME%\bin` to your `PATH` variable.

3. **Verify Installation**:
   - Run `ant -version` in Command Prompt to check if Ant is installed correctly.

### Compile and Run the Game

This project comes with a `build.xml` file for easy compilation and execution.

To compile the code, use the following Ant command:
```bash
ant compile
```

To run the compiled code, use:
```bash
ant run
```

You can specify the sequence of levels
to play by passing arguments to the ant run command like this:
```bash
ant -Dargs="1 3 2 1 9 1 bla 3 3" run
```
The numbers and strings represent the order of levels that will be loaded during the game.
 
## Controls

- **Left Arrow**: Move paddle left
- **Right Arrow**: Move paddle right
- **Space**: Exit the game after loss/win
- **P**: Pause the game

## Photos 
![Screenshot 2024-08-21 204756](https://github.com/user-attachments/assets/532d8775-fa67-4206-8d8d-1f686c679869)
![Screenshot 2024-08-21 204813](https://github.com/user-attachments/assets/9c2dbfd1-61a0-4c17-b466-fd3b7d822461)
![Screenshot 2024-08-21 204832](https://github.com/user-attachments/assets/1d9046b3-a9f4-4b78-925e-f6e7debf0248)
