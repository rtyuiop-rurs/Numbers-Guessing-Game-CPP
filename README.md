# Numbers-Guessing-Game-CPP
# Even/Odd Guessing Game

A simple C++ console game where players guess whether a randomly generated number is even or odd.

## How to Play

1. **Set the Range**: When the program starts, enter the minimum and maximum values for the random number range
2. **Choose Attempts**: Specify how many guesses you'd like to have
3. **Make Guesses**: For each attempt, type "even" or "odd" to guess the number's parity
4. **Win Condition**: Guess correctly before running out of attempts to win!
5. **Play Again**: After each round, choose whether to continue with a new random number

## Features

- Input validation for all user inputs
- Customizable number range
- Adjustable number of attempts
- Case-insensitive play again option
- Clear feedback for correct/incorrect guesses

## Requirements

- C++ compiler with C++17 support or later
- `Random.h` header file (must be in the same directory)

## Building and Running

```bash
g++ -std=c++17 main.cpp -o game
./game
```

## Game Rules

- The program generates a random number within your specified range
- You must guess whether this number is even or odd
- You have a limited number of attempts (chosen by you)
- Type "even" or "odd" (lowercase) to make your guess
- The game reveals the actual number at the end of each round

Enjoy testing your intuition about numbers!
