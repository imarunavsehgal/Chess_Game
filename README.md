# Chess_Game
# ♟️ Web Chess Game

A fully interactive web-based chess game implemented using **JavaScript**, **jQuery UI**, and **Bootstrap**. The game supports drag-and-drop functionality and visual cues for legal moves and attacks. The board UI and logic simulate a basic chess environment in the browser.

---

## 🎯 Features

- Interactive chessboard with draggable pieces
- Click-based and drag-and-drop piece movement
- Highlighting of possible move paths
- Capture/kill animations for attacking pieces
- Color-coded cells for movement and attack options
- Minimalist design with Bootstrap layout
- Responsive styling for supported devices

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3** (`styles.css`, Bootstrap 3, FontAwesome)
- **JavaScript** (with jQuery and jQuery UI)
- **jQuery UI** for drag-and-drop functionality
- **Bootstrap** for styling and layout

---

## 📁 File Structure
├── index.html # Main HTML structure
├── styles.css # Custom game styles
├── script.js # Game logic and click/drag handlers
├── bootstrap.min.css # Bootstrap framework (v3.3.7)
├── font-awesome.min.css # FontAwesome icons
├── normalize.css # CSS reset
├── bootstrap.min.js # Bootstrap JS
├── jquery-ui.min.js # jQuery UI for drag-and-drop


---

## 🚀 How to Run the Project

1. **Download or Clone the Repository**:
git clone https://github.com/yourusername/web-chess-game.git

Open the Game in Your Browser:

2. **Double-click on the index.html file or open it via a browser**:
file:///path-to-project/index.html
No server or build tools required.

🎮 Controls & Gameplay
Click or drag any piece to see available moves.
Valid move paths are highlighted in yellow.
Attackable enemy pieces are highlighted in red.
Drop the piece to a highlighted cell to move.
Movement logic is handled via script.js using factory-based object creation for each piece type.

📌 Notes
This is a local-only, two-player board game simulation.
Does not enforce full chess rules like check, checkmate, en passant, castling, or turns.
Primarily for learning and demonstration of DOM manipulation and game logic in JavaScript.
