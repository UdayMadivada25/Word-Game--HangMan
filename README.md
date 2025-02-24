# Word-Game--HangMan 🎯

A simple **Hangman** word game implemented in Python. The game selects a random word from a predefined list, and the player has to guess it letter by letter before running out of lives.

## 🚀 Features
- Random word selection from a word list.
- ASCII art for visual representation of the game stages.
- Tracks correct and incorrect guesses.
- Displays remaining lives.
- Notifies the player of wins or losses.

## 🛠️ Files Overview
- **main.py** → The main game logic, including user input handling and win/loss conditions.
- **hangman_words.py** → Contains a list of words used for the game.
- **hangman_art.py** → Includes ASCII art for the hangman stages and game logo.

## 📜 How to Play
1. The game starts by displaying an empty word representation (`_ _ _`).
2. You guess letters one by one.
3. If the guessed letter is in the word, it gets revealed in the correct position.
4. If the guessed letter is incorrect, you lose a life.
5. The game ends when:
   - You correctly guess the word (**You win! 🎉**).
   - You run out of lives (**Game Over! ❌**).

## 🏗️ Installation & Running the Game
1. Clone this repository:
   ```sh
   git clone https://github.com/UdayMadivada25/Word-Game--HangMan.git
