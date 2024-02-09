# Pong Game

This Pong game is a classic table tennis-themed arcade sports game featuring a simple yet engaging two-dimensional graphical user interface. It is developed using Python and utilizes the 
Turtle graphics library for rendering. The game supports two players with paddle controls on either side of the screen, a bouncing ball, and a scoreboard to keep track of each player's points.

## Features

- Two-Player Gameplay: Each player controls a paddle on either side of the screen, allowing for competitive play.
- Automatic Scoring System: The game includes a scoreboard displayed at the top of the screen, updating in real-time as players score points.
- Collision Detection: The game detects collisions between the ball and the paddles, as well as the ball and the top and bottom walls, to appropriately reflect the ball's trajectory.
- Adjustable Ball Speed: The ball's speed increases slightly with each paddle hit, making the game progressively more challenging.
- Reset Mechanism: Whenever a player scores, the ball resets to the center of the screen, and the game continues until it is manually stopped.

## Prerequisites

To run this game, you will need:

- Python installed on your system.
- The Turtle graphics library (comes pre-installed with Python).

## Installation

- Clone this repository or download the source code.
- Ensure you have Python installed on your system.

## Running the Game

To start the game, navigate to the directory containing the game files in your terminal or command prompt and run the following command:

```bash
python main.py
```

## Controls

- Right Paddle (Player 1): Use the "Up" and "Down" arrow keys to move the right paddle up and down.
- Left Paddle (Player 2): Use the "W" and "S" keys to move the left paddle up and down.

## Gameplay

The game begins immediately after launching. Players control their respective paddles to hit the ball back and forth. If the ball passes a paddle and hits the edge of the screen, the opposing 
player scores a point, and the ball is reset to the center. The scoreboard updates in real-time to reflect the current score.

