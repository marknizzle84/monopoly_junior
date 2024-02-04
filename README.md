# Monopoly Junior Simulator

This Python script simulates the Monopoly Junior board game with specified rules.

## Overview

The script models the Monopoly Junior game with player turns, property ownership, and chance card events. Players take turns rolling dice, moving around the board, and interacting with various board spots.

## How to Run

1. Make sure you have Python installed on your system.
2. Open a terminal.
3. Navigate to the directory containing the script.
4. Run the following command:

```bash
python monopoly_junior_simulator.py -p PLAYER_NAMES -m [MONOPOLY_RULES] -v
```

### Options

- `-p PLAYER_NAMES`: Specify the names of the players (2 to 4 players).
- `-m`: Enable regular Monopoly rules (optional).
- `-v`: Enable verbose mode for detailed output (optional).
- `-g GAMES`: Specify the number of games to simulate (default is 1).

## Example

```bash
python monopoly_junior_simulator.py -p Alice Bob -m -v
```

This will simulate a Monopoly Junior game with players Alice and Bob, using regular Monopoly rules and providing verbose output.

## Game Rules

- Each player starts with 10 ticket booths (12 if only 2 players).
- Players take turns rolling a die and moving around the board.
- Chance cards trigger events such as collecting money, moving to specific spots, or gaining free ticket booths.
- Players can buy properties, pay rent to other players, and go bankrupt.

## Monopoly Rules

If the `-m` option is used, regular Monopoly rules apply:

- Bankrupt players transfer all properties to the current payee.
- The game continues until only one player remains or a set number of games are completed.

## Analysis

After simulating multiple games, the script provides an analysis of each player's performance, including total cash and the number of wins.

Feel free to customize the script and adjust parameters according to your preferences.
```

Feel free to customize or add more details based on your preferences and requirements!