🎮 Tic-Tac-Toe Game
A simple, two-player Tic-Tac-Toe game built with HTML, CSS (using Tailwind CSS), and JavaScript. This project is a great demonstration of fundamental web development concepts including DOM manipulation, event handling, and basic game logic.

✨ Features
Two-Player Gameplay: Enjoy classic Tic-Tac-Toe with a friend.

Intuitive UI: Clean and modern interface designed with Tailwind CSS.

Responsive Design: Plays well on various screen sizes.

Game Status Display: Clearly shows whose turn it is and announces the winner or a draw.

Reset Functionality: Easily start a new game at any time.

🚀 How to Play
Clone the Repository:

git clone <https://github.com/Kuntaarun/Tic_tac_toe_Game>
cd <Tic_tac_toe_Game>

Open the File:
Simply open the index.html file in your web browser. You can do this by double-clicking the file or by dragging it into your browser window.

🛠️ Technologies Used
HTML5: For the basic structure of the game.

CSS3: Custom styles and layout.

Tailwind CSS: A utility-first CSS framework for rapid and responsive styling.

JavaScript: For game logic, event handling, and dynamic content updates.

💡 How it Works
The game logic is entirely handled by JavaScript:

board Array: Represents the 3x3 game grid, storing 'X', 'O', or empty strings.

currentPlayer: Keeps track of whose turn it is.

gameActive: A boolean flag to determine if the game is still in progress.

winningConditions: An array of arrays defining all possible winning lines on the board.

initializeGame(): Sets up the initial state of the board and UI.

handleCellClick(): Processes a player's move, updates the board, and triggers game status checks.

checkGameStatus(): Determines if there's a winner, a draw, or if the game should continue.

switchPlayer(): Alternates between 'X' and 'O' turns.