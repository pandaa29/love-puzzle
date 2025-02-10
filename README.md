# love-puzzle# Love Puzzle

This is a simple puzzle game where you can drag and drop pieces to complete the puzzle. The puzzle image is randomized each time you complete it.

## Project Structure


- `baby.jpg`: The image used for the puzzle.
- `index.html`: The main HTML file that sets up the structure of the puzzle.
- `script.js`: The JavaScript file that contains the logic for the puzzle game.
- `style.css`: The CSS file that styles the puzzle game.

## How to Run

1. Open `index.html` in your web browser.
2. Drag and drop the puzzle pieces to their correct positions.
3. Once all pieces are correctly placed, the puzzle will reset with a new randomized image.

## JavaScript Functions

- `randomizeImage()`: Randomizes the puzzle image and positions of the pieces.
- `reloadPuzzle()`: Resets the puzzle pieces to their initial state.
- `allowDrop(ev)`: Allows dropping of elements.
- `drag(ev)`: Handles the drag start event.
- `drop(ev)`: Handles the drop event and checks if the piece is placed correctly.

## CSS Classes

- `.first`, `.secon`, `.third`, `.fourt`, `.fifth`, `.sixth`, `.seven`, `.eight`, `.ninth`: Classes for each puzzle piece.
- `.clicked`: Applied to a piece when it is clicked.
- `.dropped`: Applied to a piece when it is correctly placed.
- `.done`: Applied to a piece when it is correctly placed and hidden.
- `.allDone`: Applied to the puzzle container when all pieces are correctly placed.

## License

This project is licensed under the MIT License.
