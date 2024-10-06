# Chess-Engine
Chess Engine Create In Pure HTML5,CSS,JS
Here's an updated README file with clear explanations and instructions:
Chess Engine: AI vs Human
Overview
A web-based chess engine built from scratch using HTML, CSS, and JavaScript, allowing users to play against a basic AI opponent.
Features
Play as white (human) against the black (AI) opponent
Move pieces using click-to-move
Basic AI decision-making using Minimax algorithm with adjustable depth
Responsive design for mobile and desktop devices
Display of move history and current turn indicator
Gameplay Methods
Player Types
white: Human player
black: AI player
Game Logic Methods
makeMove(piece, fromSquare, toSquare): Handles piece movement and updates board state
generateMoves(piece, square): Returns possible moves for a given piece
evaluation(): Calculates board score for AI decision-making
minimax(depth, board): AI's decision-making algorithm
Minimax Algorithm
Depth: Adjustable (default=3)
Description: Recursive algorithm exploring possible moves and their outcomes
Technical Details
Built using HTML5, CSS3, and JavaScript (ES6+)
No external libraries or frameworks used
Custom implementation of chess rules and AI algorithm
Getting Started
Installation
Clone the repository: git clone https://github.com/your-username/Chess-Engine.git
Open index.html in your browser to start playing
Usage
Start a new game by clicking the "New Game" button
Make moves by dragging pieces or clicking on the destination square
Observe AI's moves and respond accordingly
Adjust Minimax depth by modifying depth variable in minimax.js file
Customizing Minimax Depth
To change the Minimax depth:
Open minimax.js file
Locate depth variable (default=3)
Update value to desired depth (e.g., 2, 4, 5)
Contributing
Contributions are welcome! Feel free to:
Report bugs or issues
Suggest improvements to AI algorithm or gameplay
Submit pull requests with your changes
License
This project is licensed under the MIT
Troubleshooting
Check console logs for errors
Verify browser compatibility
