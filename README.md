# Battleship Game

A console-based implementation of the classic **Battleship** game where you compete against a computer opponent. The game features intelligent computer targeting, customizable game length, and replay functionality.

## Features

- Random placement of **5 ships** for both the player and the computer.
- Ship sizes:
  - 2
  - 3
  - 3
  - 4
  - 5
- Customizable number of turns before the game begins.
- Computer AI with basic strategy:
  - Makes random moves initially.
  - Once it hits part of a ship, it searches the surrounding cells to locate the remaining parts instead of continuing with completely random moves.
- At the end of the selected number of turns, the player is given the option to continue by adding more turns.
- Winner is determined by the total number of successful hits on the opponent's ships.
- Option to play multiple games without restarting the program.

## Game Rules

1. At the start of the game, the computer randomly places all ships for both players.
2. Enter the number of turns you would like to play.
3. Each turn:
   - You select a coordinate to attack.
   - The computer makes its move.
4. When all allotted turns are used, you can choose to:
   - Continue with additional turns, or
   - End the game.
5. The player with the higher number of successful ship hits is declared the winner.
6. After the results are displayed, you can choose to play another game.

## Requirements

- Python 3.x

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Wurdalpoke/battleship/blob/main/code.txt
   ```

2. Navigate to the project folder:

   ```bash
   cd battleship
   ```

3. Run the program:

   ```bash
   python main.py
   ```


## Future Improvements

- Difficulty levels for the computer AI.
- Graphical user interface (GUI).
- Smarter AI using probability-based targeting.
- Save game functionality.
- Multiplayer over a network.

## Author

Harshita Samriddhi
