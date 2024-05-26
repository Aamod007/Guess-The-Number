# Guess the Number Game in Java

This is a simple "Guess the Number" game implemented in Java. The computer will think of a random number between 1 and 1000, and the user will try to guess it. The game will provide hints (too high, too low) after each guess until the user guesses correctly.

## Features

- Random number generation by the computer.
- User input for guessing the number.
- Hint messages for incorrect guesses (too high, too low).
- Display of the number of guesses made by the user.

## How to Play

1. Clone the repository:
    ```sh
    git clone https://github.com/Aamod007/guess-number-game-java.git
    ```
2. Navigate to the project directory:
    ```sh
    cd guess-number-game-java
    ```
3. Compile the Java program:
    ```sh
    javac GuessNumberGame.java
    ```
4. Run the Java program:
    ```sh
    java GuessNumberGame
    ```

## Gameplay Instructions

- The game will start by displaying a message asking the user to guess the number.
- Enter a number and press Enter.
- If the guessed number is higher than the computer's number, the game will display "Sorry, the number you guessed is too high".
- If the guessed number is lower than the computer's number, the game will display "Sorry, the number you guessed is too low".
- Keep guessing until you guess the correct number, and the game will display "Congratulations! Your guess is correct!".
- After the game ends, the total number of guesses made by the user will be displayed.

## Example

Please guess the number:
500
Sorry, the number you guessed is too low
750
Sorry, the number you guessed is too high
625
Sorry, the number you guessed is too low
687
Congratulations! Your guess is correct!
You found the number in 4 guesses


## Code Overview

- `GuessNumberGame` class: Contains the main method and game logic.
  - `startGame` method: Starts the game loop, checks user input, and compares it with the computer's number.
  - `getNumberByComputer` method: Generates a random number for the user to guess.
  - `getUserGuessedNumber` method: Reads the user's input for their guessed number.

## Contributing

Feel free to fork this repository and contribute by submitting pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
