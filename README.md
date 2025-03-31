# Wordle Game

A simple web-based Wordle clone built with HTML, CSS, and vanilla JavaScript. In this game, players have five attempts to guess a five-letter programming-related word of the day.

Each guess provides color-coded feedback:
- **Green** for correct letters in the correct position
- **Yellow** for correct letters in the wrong position
- **Gray** for incorrect letters

The correct word changes daily, determined by the current date, and includes an accompanying definition to enhance your understanding of programming concepts.

## Features

- Five-letter word guessing game
- Educational word definitions shown internally via console
- Word validation through external API
- Color-coded hints for each letter
- Five attempts per game
- Clean and minimalistic UI

## Usage

1. Clone or download the repository.
2. Open `index.html` in a modern browser.
3. Start typing your guesses directly from the keyboard and press `Enter` to submit.
4. Use `Backspace` to remove a letter.

The game uses standard DOM manipulation, fetch requests for validation, and lightweight logic to manage game state, making it suitable for beginner developers to study or extend.
