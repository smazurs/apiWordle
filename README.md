# API-Driven Wordle Game

This is a minimalistic, web-based implementation of the popular Wordle game. The game fetches a random 5-letter word from an external API and challenges the player to guess it within six attempts.

## Features

- **Random Word Generation**: The game fetches a random 5-letter word from the [Random Word API](https://random-word-api.herokuapp.com/).
- **Interactive Grid**: A clean and responsive 5x6 grid dynamically updates based on user input.
- **Keyboard Input Handling**: The game supports keyboard input, including letter entry, backspace for corrections, and Enter to submit guesses.
- **Feedback on Guesses**: The game provides color-coded feedback (green for correct letters, yellow for present but misplaced letters, and gray for absent letters).
- **Restart Functionality**: A restart button allows the player to reset the game at any time.

### How to Play

1. **Start the game**: The game automatically fetches a random word and sets up the grid when the page loads.
2. **Enter your guesses**: Type your guess using your keyboard. Use the Backspace key to correct mistakes.
3. **Submit your guess**: Press Enter to submit your guess. The game will provide feedback by color-coding the tiles:
   - **Green**: Correct letter in the correct position.
   - **Yellow**: Correct letter but in the wrong position.
   - **Gray**: Incorrect letter.
4. **Win or Lose**: If you guess the word correctly, you'll see a congratulations message. If you exhaust your six attempts without guessing correctly, the correct word will be revealed.
5. **Restart the game**: Click the "Restart Game" button to play again.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Wordle](https://www.nytimes.com/games/wordle/index.html) - The original game that inspired this project.
- [Random Word API](https://random-word-api.herokuapp.com/) - For providing the random words used in the game.
