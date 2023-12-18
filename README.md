# Scissors Paper Stone Game

## Overview

This is a simple Scissors Paper Stone game that uses a webcam to capture the user's hand gesture and determine their choice. The game allows the user to play against the computer, which randomly selects its choice.

The game includes the following features:

- **User Interaction**: The user can make a choice by showing a gesture (Scissors, Paper, or Stone) to the webcam.
- **Computer Opponent**: The computer randomly selects its choice (Scissors, Paper, or Stone).
- **Game Logic**: The game determines the winner based on the choices made by the user and the computer.
- **Score Tracking**: The user's and computer's scores are displayed, and the winner of each round is announced.

## How to Play

1. Click the "Start Video Camera" button to initialize the webcam and start making your choice.
2. Show a hand gesture (Scissors, Paper, or Stone) to the webcam.
3. The computer will also make a random choice.
4. The winner of the round is determined, and the scores are updated.
5. Click the "Start Game" button to play another round.

## Technologies Used

- **HTML**: For structuring the content.
- **CSS**: For styling.
- **JavaScript**: For game logic and webcam interaction.
- **TensorFlow.js**: For running machine learning models in the browser.
- **Teachable Machine Image**: For creating and training a custom image classification model.
- **Bootstrap**: For styling and layout.

## How to Run Locally

To play the Scissors Paper Stone game locally:

1. Clone this repository.
2. Open the `index.html` file in a web browser.
3. Click the "Start Video Camera" button to initialize the webcam.
4. Show a hand gesture to the webcam to make your choice.
5. Enjoy playing against the computer!

## Acknowledgments

- The game uses the [Teachable Machine Image](https://github.com/googlecreativelab/teachablemachine-community/tree/master/libraries/image) library for image classification.

Feel free to explore the game, improve its features, or customize it according to your preferences.
