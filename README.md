# Web Tetris Game

This is a simple web-based Tetris game created using HTML5, CSS, and JavaScript. The game is playable directly in a web browser with a canvas-based interface.

## Features
- **Canvas Rendering**: The game board and pieces are drawn on a `<canvas>` element.
- **Score Tracking**: The score updates as rows are cleared.
- **Piece Rotation and Movement**: The player can rotate and move pieces left, right, or down.
- **Responsive Controls**: The game responds to keyboard events for controlling the falling pieces.
- **Collision Detection**: Pieces will stop falling when they collide with others or the bottom of the game area.

## Game Controls
- **Arrow Left (←)**: Move the piece left.
- **Arrow Right (→)**: Move the piece right.
- **Arrow Down (↓)**: Drop the piece faster.
- **Key Q**: Rotate the piece counter-clockwise.
- **Key W**: Rotate the piece clockwise.

## How to Play
1. Open the HTML file in a web browser.
2. Use the arrow keys and Q/W to control the falling Tetriminos (pieces).
3. The game will end if new pieces cannot be placed.

## Code Structure
- **HTML**: Contains the layout, including a `<canvas>` element for rendering the game and a score display.
- **CSS**: Basic styling for the canvas and score display.
- **JavaScript**:
  - **Arena & Pieces**: Creates the game grid (arena) and various Tetriminos.
  - **Collision Handling**: Checks for collisions between pieces and updates the arena.
  - **Game Loop**: Uses `requestAnimationFrame` to continuously update the game state and render it.
  - **Event Handling**: Listens for keypresses to move and rotate pieces.

## How to Run
1. Download the `index.html` file to your local machine.
2. Open the file with any modern web browser (Chrome, Firefox, Edge, etc.).
3. Start playing by using the arrow keys and rotate with Q/W.

## License
This game is open-source and free to use. Enjoy!
