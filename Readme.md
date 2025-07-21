# Perfect Guess

A simple Python "Guess the Number" game.

## How to Play

1. The program randomly selects a number between 1 and 100.
2. You try to guess the number.
3. After each guess, the program tells you if you should guess higher or lower.
4. The game counts your guesses and tells you when you guess correctly.
5. If you beat the previous high score (fewest guesses), your score is saved in `score.txt`.

## Requirements

- Python 3.x

## Usage

1. Make sure you have a `score.txt` file in the same directory as `perfect_guess.py`.  
   (You can create it manually and put a large number like `1000` in it for the first run.)
2. Run the game:

   ```sh
   python perfect_guess.py
   ```

3. Follow the prompts to guess the number.

## Files

- [`perfect_guess.py`](perfect_guess.py): Main game script.
- `score.txt`: Stores the best (lowest) number of guesses.

## Example

```
Enter your guess: 50
Enter a larger number:
Enter your guess: 75
Enter a smaller number:
Enter your guess: 63
You guessed it right..
You guessed the number in 3 guesses.
You have just broken the high score.
```
