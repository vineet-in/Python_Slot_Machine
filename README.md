# Python_Slot_Machine

Here’s a simple `README.md` for your slot machine project:

---

# Slot Machine Game 🎰

This is a console-based slot machine game built in Python. The player deposits an initial amount of money, chooses how many lines to bet on, and places a bet for each line. The slot machine spins, and if the player matches symbols across the lines, they win based on the value of the symbols.

## Features

- **Deposit System**: Players can deposit an amount to their balance.
- **Betting Lines**: Players can choose to bet on 1 to 3 lines.
- **Slot Machine Symbols**: The game uses four different symbols ("A", "B", "C", "D"), each with varying frequency and value.
- **Winning System**: Players win based on matching symbols on lines, with different symbols yielding different rewards.
- **Balance Management**: The total balance is updated based on wins and losses after each spin.

## Symbols & Values

- **A**: Appears 2 times, worth 5x the bet.
- **B**: Appears 4 times, worth 4x the bet.
- **C**: Appears 6 times, worth 3x the bet.
- **D**: Appears 8 times, worth 2x the bet.

## Getting Started

### Prerequisites

- Python 3.x should be installed on your machine.

### Running the Game

1. Clone the repository or download the script.
2. Run the script using Python.

```bash
python slot_machine.py
```

### How to Play

1. The game starts by asking how much you want to deposit.
2. After depositing, you choose how many lines (1-3) to bet on.
3. Place a bet amount for each line (minimum $1, maximum $100).
4. The slot machine will spin and display the results.
5. If the same symbol appears on any line across all columns, you win according to the symbol's value.
6. The game continues until you quit by pressing "q", or when your balance reaches zero.

### Example Gameplay

```bash
What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $10
You are betting $10 on 2 lines. Total bet is equal to: $20
A | B | C
B | C | A
D | A | B
You won $0.
You won on lines:
Current balance is $80
Press enter to play (q to quit).
```

## Functions

- `deposit()`: Prompts the user to enter a deposit amount.
- `get_number_of_lines()`: Allows the user to select how many lines to bet on.
- `get_bet()`: Asks the user for the amount they wish to bet on each line.
- `get_slot_machine_spin()`: Generates a random outcome for the slot machine based on symbol counts.
- `print_slot_machine()`: Displays the slot machine's results.
- `check_winnings()`: Checks if any lines have matching symbols and calculates winnings.
- `spin()`: Simulates a single round of the slot machine.
- `main()`: Controls the game loop, manages the player's balance, and handles quitting the game.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

### Enjoy the game and good luck! 🍀
