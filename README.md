# Pong Game

This project is part of my 100 days of code in Python, and it represents my 22nd day.
A simple implementation of the classic Pong game using Python and the Turtle graphics library.

## How to Play

- Control the left paddle using the 'w' key to move up and the 's' key to move down.
- Control the right paddle using the Up arrow key to move up and the Down arrow key to move down.

## Game Rules

- The game features a bouncing ball that collides with the paddles and walls.
- Points are awarded when the ball passes the opposite side of the screen.
- The left player scores a point when the ball passes the right side, and vice versa.
- The game continues until the user closes the window.

## Files

- `main.py`: Contains the main game loop and setup.
- `ball.py`: Defines the Ball class responsible for the ball's behavior.
- `paddle.py`: Defines the Paddle class for player-controlled paddles.
- `scoreboard.py`: Defines the Scoreboard class to keep track of scores.

## How to Run

- python3 -m venv venv
- source venv/bin/activate
- python3 main.py
