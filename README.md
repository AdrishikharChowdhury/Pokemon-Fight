# Pokemon Battle Simulation

## Overview
This is a simple console-based Pokemon battle simulation program written in C. Players can choose from a selection of Pokemon, each with different attributes, and engage in head-to-head battles. The game includes features such as attack moves, defense strategies, and a visual representation of the battle stadium.

## Features
- **Pokemon Selection**: Players choose their team from a predefined list of Pokemon.
- **Battle Mechanics**: Each Pokemon has attributes like HP, Attack, Defense, and Speed which influence the outcome of battles.
- **Turn-Based Combat**: Players take turns attacking each other’s Pokemon until one player’s team is completely defeated.
- **Dynamic Display**: The program displays the current state of the battle, including stats for each Pokemon.

## Program Structure
- **Struct `pokemon`**: Defines the attributes of each Pokemon.
- **Function List**:
  - `sentenceCase()`: Converts a string to sentence case.
  - `stadium()`: Displays the battle stadium.
  - `playerch()`: Allows the player to choose a Pokemon.
  - `battlestadium()`: Displays the stats of the battling Pokemon.
  - `attack()`: Handles the attack moves during battle.
  - `H2H1()`: Manages the head-to-head battle logic.
  - `speedofPokemon()`: Calculates the speed of a Pokemon based on its name.
  - `choosePokemon()`: Allows the player to choose their Pokemon team.
  - `freePokemon()`: Frees allocated memory for Pokemon names.
  - `showParty()`: Displays the player's Pokemon team.
- **`main()`**: The entry point of the program, where the game flow is controlled.

## How to Compile and Run
1. **Compilation**: Use GCC or any other C compiler to compile the code.
   ```sh
   gcc -o pokemon_battle pokemon_battle.c
    ./pokemon_battle

## Game Flow

### Player Name Input
The program prompts each player to enter their name. This personalization adds an engaging element to the game as each player becomes a part of the simulation.

### Team Selection
Each player selects three Pokemon for their team. The selection includes different types of Pokemon, each with unique attributes such as HP, Attack, Defense, and Speed. This strategic choice influences the battle's outcome.

### Battle Begins
Players choose which Pokemon to send out first. This decision is crucial as the selected Pokemon will initiate the battle and potentially gain an early advantage.

### Turn-Based Battle
Players take turns attacking until all of one player's Pokemon faint. The battle mechanics include various attack options and strategies, such as primary and secondary attacks, Leer to reduce speed, and defensive moves to increase defense. Players must think tactically to outmaneuver their opponent.

### Declare Winner
The game announces the winner and ends. Once all of one player's Pokemon faint, the remaining player is declared the winner, concluding the game.

Enjoy battling with your favorite Pokemon and may the best trainer win!
## Example Output
        Enter name of the 1st player: Ash
        Enter name of the 2nd player: Gary
        
        Ash's Team:
        1. Charmander
        2. Squirtle
        3. Bulbasaur
        
        Gary's Team:
        1. Vulpix
        2. Psyduck
        3. Oddish
        
        Battle Stadium
        
        Ash's turn:
        Choose move (1-4):
        1. Primary Attack
        2. Secondary Attack
        3. Leer
        4. Defense
        Your move: 1
        
        Charmander was hit by primary attack. Lost 25 HP.
        ...
        Gary wins!

        # Pokemon Battle Simulation

## Issues
If you encounter any issues or bugs, please report them using the Issues tab in the repository. Include details about the problem and steps to reproduce it.

## Contributing
Contributions are welcome! Here’s how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or suggestions, feel free to contact the project maintainer.

## Notes
- Ensure that the necessary header files (`stdio.h`, `stdlib.h`, `string.h`, `ctype.h`, `conio.h`) are included.
- Use `getch()` for waiting for a key press after important messages.
- Proper memory allocation and deallocation are crucial to avoid memory leaks.
- The `speedofPokemon()` function calculates the speed of a Pokemon based on the alphabetical values of its name.
- This program is a basic representation of a Pokemon battle and can be expanded with more features and improved user interface.

Enjoy battling with your favorite Pokemon!
