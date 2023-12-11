# Hangman Game in Perl

- The target word is represented by a series of dashes, indicating the number of letters in the word.
- Players attempt to guess the word by observing the displayed dashes. The game prompts users to enter one letter at a time.
- If the user's suggested letter is present in the word, the program reveals it in all correct positions.
- In case of an incorrect letter, the player's available guesses decrease. Six guesses are provided, and for each incorrect choice, a segment of a hanged man stick figure is drawn.
- The game concludes in two scenarios:
  - If the player successfully completes the entire word, they emerge victorious.
  - If the number of attempts exceeds the limit, resulting in the completion of the hangman diagram, the player loses the game.
