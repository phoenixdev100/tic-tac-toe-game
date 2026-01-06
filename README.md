<div align="center">

# 🎮 Tic-Tac-Toe Game

### A classic, interactive Tic-Tac-Toe game built with vanilla JavaScript, HTML, and CSS. Play against a friend in this beautifully designed, responsive web application.

![Tic-Tac-Toe Game](https://img.shields.io/badge/Game-Tic--Tac--Toe-blue) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

</div>

## 🌟 Features

- **Two-Player Gameplay**: Play with a friend on the same device
- **Winner Detection**: Automatic detection of winning patterns
- **Game Reset**: Reset the game at any time or start a new game after winning
- **Responsive Design**: Clean, modern UI that works on all screen sizes
- **Visual Feedback**: Clear indication of player turns (X and O)
- **Smooth Animations**: Polished user experience with shadow effects

## 🎯 Demo

The game features:
- A 3x3 grid with interactive buttons
- Alternating turns between Player O and Player X
- Winner announcement with congratulations message
- Reset and New Game functionality

<div align="center">

## 🚀 Getting Started

</div>

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/phoenixdev100/tic-tac-toe-game.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd tic-tac-toe-game
   ```

3. **Open the game**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```
   - Then navigate to `http://localhost:8000` in your browser

<div align="center">

## 🎮 How to Play

</div>

1. **Start the Game**: Open the application in your browser
2. **Player O goes first**: Click any empty box to place your mark
3. **Alternate Turns**: Players take turns placing X and O
4. **Win Condition**: Get three of your marks in a row (horizontally, vertically, or diagonally)
5. **Reset**: Click "Reset game" to clear the board or "New Game" after a winner is declared

## 🛠️ Technical Details

### Technologies Used

- **HTML5**: Semantic markup for game structure
- **CSS3**: Modern styling with flexbox layout
- **Vanilla JavaScript**: Pure JS for game logic (no frameworks)

### Key Features Implementation

#### Win Pattern Detection
The game checks 8 possible winning patterns:
- 3 horizontal rows
- 3 vertical columns
- 2 diagonal lines

#### Game State Management
- Tracks current player turn
- Disables boxes after they're clicked
- Enables/disables all boxes on reset

#### UI/UX Elements
- Color scheme: Teal background (#548687) with yellow boxes (#ffffc7)
- Responsive sizing using viewport units (vmin)
- Box shadows for depth effect
- Hidden/shown winner message container

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

## 👤 Author

**phoenixdev100**

- GitHub: [@phoenixdev100](https://github.com/phoenixdev100)

## 🙏 Acknowledgments

- Classic Tic-Tac-Toe game rules
- Inspired by traditional pen-and-paper gameplay
- Built as a learning project for vanilla JavaScript

## 📞 Support

If you have any questions or run into issues, please open an issue on GitHub.

---

**Enjoy the game! May the best player win! 🏆**
