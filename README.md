# Turtle Movement Game

This is a JavaScript game designed to teach children how to use correct terminology to describe movements and turns. The game features a 11x11 grid and a turtle character that both the player and computer can move by giving instructions.

## Features
- 11x11 grid with a turtle starting at the center
- Player and computer take turns giving movement instructions
- Player types instructions; computer moves the turtle
- Computer gives instructions; player clicks the destination square
- Supported instructions:
  - `forward <number>`: Move forward by the specified number of squares
  - `back <number>`: Move backward by the specified number of squares
  - `left <number>`: Move left by the specified number of squares
  - `right <number>`: Move right by the specified number of squares
  - `turn clockwise`: Turn 90 degrees clockwise
  - `turn anticlockwise`: Turn 90 degrees anti-clockwise
  - **Short instructions are also supported:**
    - `f <number>`: forward
    - `b <number>`: back
    - `l <number>`: left
    - `r <number>`: right
    - `c`: turn clockwise
    - `ac`: turn anticlockwise

## Getting Started
1. Open the project in VS Code
2. Run a local server to view the game in your browser (e.g., `npx serve .` or use the Live Server extension)

## License
MIT