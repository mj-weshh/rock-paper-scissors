# Rock, Paper, Scissors Game

This is a simple console-based Rock, Paper, Scissors game implemented in Python.

## Description

The script allows a user to play the classic Rock, Paper, Scissors game against a computer opponent. The user is prompted to input their choice ('r' for rock, 'p' for paper, and 's' for scissors), and the computer randomly selects its choice. The winner is determined based on the game rules, and the result is displayed.

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/mj-weshh/rock-paper-scissors.git
   ```

2. Change into the project directory:

   ```bash
   cd rock-paper-scissors
   ```

### Usage

Run the script using the following command:

```bash
python rock_paper_scissors.py
```

Follow the on-screen instructions to input your choice, and the result of the game will be displayed.

## Rules

- Rock crushes scissors.
- Scissors cuts paper.
- Paper covers rock.

## Functionality

The script consists of two main functions:

- `play()`: Initiates the game, takes user input, generates a random choice for the computer, and determines the winner based on the game rules.
- `winner(player, opponent)`: Determines the winner of a single round based on the choices made by the player and the computer.

## Contributions

Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.
