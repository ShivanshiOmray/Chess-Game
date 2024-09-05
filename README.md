Chess-Game : https://chess-game-68wp.onrender.com
# Chess Game

A real-time multiplayer chess game built using Node.js, Socket.io, and the Chess.js library. 
This application allows two players to connect and play a game of chess in real time with a sleek and responsive interface.

## Features

- **Real-Time Gameplay**: Players can make moves in real-time, with the board updating instantly using Socket.io.
- **Multiplayer Support**: Supports two players, one controlling the white pieces and the other controlling the black pieces.
- **Spectator Mode**: Additional users can join as spectators to watch the game.
- **Drag and Drop**: Intuitive drag-and-drop interface for moving pieces.
- **Responsive Design**: The chessboard adapts to different screen sizes, with the view flipping for the black player.

## How to Play

### Player Roles:
- The first connected player will automatically be assigned the white pieces.
- The second player will be assigned the black pieces.
- Additional users can join as spectators and watch the game in real time.

### Making a Move:
- Drag a piece from its current square to a valid target square.
- The server will validate the move and update the board for all connected clients.

### Winning the Game:
- The game follows standard chess rules, including check, checkmate, and stalemate.

## Technologies Used

- **Node.js**: For server-side logic and handling client connections.
- **Socket.io**: For real-time communication between the server and clients.
- **Chess.js**: To handle the game logic, including validating moves and tracking the game state.
- **EJS**: For rendering the server-side HTML templates.

