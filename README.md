🧩 Sudoku Game
A fully interactive, responsive Sudoku game built with HTML, CSS, and vanilla JavaScript. This web-based puzzle allows players to select difficulty levels, track their time and mistakes, and use hints while solving randomly generated Sudoku boards.

🚀 Features
🎮 Interactive 9x9 Sudoku grid

🎯 Four difficulty levels: Easy, Medium, Hard, Expert

⏱️ Timer to track play duration

❌ Mistake counter (game ends after 3 mistakes)

💡 Hint system to reveal a correct cell

✅ Real-time validation and solution checking

🔁 Reset and New Game controls

📱 Responsive design for mobile and desktop

📂 File Structure
sudoku-game.html – Main HTML file with embedded styles and scripts

🛠️ How It Works
Puzzle Generation:

A complete valid Sudoku solution is generated.

Numbers are removed from the grid based on selected difficulty.

Gameplay:

Users fill in the empty cells.

Inputs are validated immediately.

Mistakes are tracked; exceeding the limit ends the game.

Timer starts automatically and stops when the puzzle is completed.

Controls:

New Game: Generates a new puzzle.

Reset: Restores the initial state of the current puzzle.

Hint: Reveals one correct number.

Check: Validates current user entries against the solution.

📦 Usage
Open in Browser
Simply open sudoku-game.html in any modern web browser.

No Dependencies
This project is self-contained and does not rely on any external libraries or frameworks.

🎨 Customization
You can adjust styles in the <style> section of the HTML file.

Modify puzzle generation logic in the generatePuzzle() or removeNumbers() functions to change difficulty behavior.

📄 License
This project is open-source and free to use under the MIT License.
