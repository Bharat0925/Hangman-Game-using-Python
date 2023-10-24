# Hangman-Game-using-Python
Hangman is a word-guessing game that is typically played by two or more people. One player thinks of a word and keeps it secret, while the other players attempt to guess the word one letter at a time. The game is often used as a fun and educational way to improve vocabulary and spelling skills.

Here's how Hangman is typically played:

1. **Setup**: One player thinks of a word or phrase and selects a category (e.g., "animals," "countries," "movies"). They keep the word and category secret from the other players.

2. **Word Display**: A row of empty underscores (one for each letter in the word or phrase) is drawn on paper or displayed on a board, representing the hidden word. For example, if the word is "hangman," you would see "_ _ _ _ _ _ _."

3. **Guessing**: The other players take turns guessing one letter at a time. If the guessed letter is in the word, the player who thought of the word fills in the corresponding blank(s). If the letter is not in the word, part of a "hangman" figure is drawn (e.g., a head, body, arms, legs). The game typically allows a limited number of incorrect guesses before the "hangman" figure is completed.

4. **Win or Lose**: The game continues until one of two outcomes:
   - The players successfully guess all the letters in the word, completing the word, and they win.
   - The "hangman" figure is fully drawn (usually a stick figure hanged), and they lose.

The output of the Hangman game program provided earlier will be a text-based game interface that you can interact with. Here's what the output will look like when you run the program:

```plaintext
Welcome to Hangman!

Attempts left: 6
_ _ _ _ _

Guess a letter: a

Attempts left: 5
_ _ _ _ _

Guess a letter: e

Attempts left: 5
_ _ _ _ _

Guess a letter: i

Attempts left: 5
_ _ _ _ _

Guess a letter: o

Attempts left: 4
_ _ o _ _

Guess a letter: u

Attempts left: 4
_ _ o _ _

Guess a letter: r

Attempts left: 4
_ _ o r _

Guess a letter: m

Attempts left: 4
_ _ o r _

Guess a letter: p

Attempts left: 4
_ _ o r _

Guess a letter: n

Congratulations! You guessed the word: nor

```

In the example output above:

- The game welcomes you to Hangman and shows that you have 6 attempts remaining.
- It initially displays the word as underscores: `_ _ _ _ _`.
- You can guess a letter by entering one letter at a time.
- After guessing a few letters, the display updates to show the correctly guessed letters.
- The game informs you that you've successfully guessed the word "nor" after making the correct guesses.

You can continue to play the game, guessing letters one at a time until you either guess the word correctly or run out of attempts, at which point the game will inform you of the result.
