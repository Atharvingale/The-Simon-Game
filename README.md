# Simon Game

The Simon Game is a classic memory game where the user must replicate an increasing sequence of button presses as the game progresses. It tests and improves your memory skills in a fun and interactive way.

## Features

- Four colored buttons (Red, Blue, Green, Yellow), each with a unique sound.
- Randomly generated sequence of button presses to challenge the user.
- Visual feedback with animations and sound effects.
- Game Over indicator with the option to restart the game.
- Levels that increase in difficulty with each correct sequence.

## Technologies Used

- **HTML**: Structure of the game interface.
- **CSS**: Styling and animations for buttons and layout.
- **JavaScript**: Core game logic and user interaction.
- **jQuery**: Simplified DOM manipulation and event handling.

## How to Play

1. Open the game in your browser.
2. Press any key to start the game.
3. Watch and listen to the sequence of button flashes and sounds.
4. Click the buttons in the same order as the sequence.
5. If you succeed, a new sequence will play with an additional step.
6. If you fail, the game will display "Game Over" and allow you to restart.

## Folder Structure

- **index.html**: The main HTML file for the game interface.
- **styles.css**: Contains all the styling for the game.
- **index.js**: The JavaScript file with game logic.
- **sounds/**: A folder containing the audio files for the game sounds.

## How to Run the Game

1. Clone this repository or download the files.
2. Ensure the `sounds` folder contains the required audio files (`red.mp3`, `blue.mp3`, `green.mp3`, `yellow.mp3`, `wrong.mp3`).
3. Open `index.html` in your browser.

## Game Logic Overview

- **Game Pattern**: A sequence of colors generated randomly.
- **User Input**: The sequence entered by the user by clicking buttons.
- **Sequence Matching**: The user's input is validated against the game's pattern.
- **Levels**: Increment when the user correctly replicates the pattern.
- **Restart**: Triggered when the user makes an incorrect selection.

## Dependencies

- jQuery (v3.7.1) is used for simplified DOM manipulation.



## License

This project is open-source and free to use.
