# Rubik's Cube Simulator

This project is a simple Rubik's Cube simulator written in JavaScript. It allows you to represent, scramble, rotate, and reset a virtual Rubik's Cube directly in the console.

## Features

- Displays a virtual representation of a Rubik's Cube
- Allows scrambling the cube with random moves
- Basic front face rotation implemented
- Solve function resets the cube to a solved state
- Console output shows the cube's current state

## How to Run

1. Clone this repository:

   git clone https://github.com/sayansonu7/rubiks-cube-simulator.git

2. Open the project in a code editor.

3. You can run the code using Node.js or directly in the browser console.

Example usage:

```js
const cube = new RubiksCube();
cube.display();   // Show the solved cube
cube.scramble();  // Scramble the cube
cube.display();   // Show the scrambled cube
cube.solve();     // Reset to solved state
