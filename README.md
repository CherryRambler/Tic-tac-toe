# 🎮 Tic-Tac-Toe Game

A simple yet interactive Tic-Tac-Toe game built using **HTML**, **CSS**, and **JavaScript**. Playable in your browser with a clean interface and real-time win/draw detection.

---

## ✨ Features

- Two-player game (X and O)
- Hover effect to show whose turn it is
- Win and draw detection with end-game messages
- Responsive grid layout
- Restart game functionality

---

## 🌐 Live Preview

You can play the game instantly without downloading by visiting:

[Live Demo on GitHub Pages](https://cherryrambler.github.io/Tic-tac-toe/)

---

## 📁 Project Structure


📁 Project Structure
bash
Copy
Edit
.
├── index.html      # HTML layout of the game
├── style.css       # Styling of game board and messages
└── script.js       # Game logic and interactivity
🚀 Getting Started
To run the game locally:

---

## New Things I Learned

- How to manipulate the DOM using JavaScript to update the game board dynamically.
- Implementing game logic for win and draw conditions.
- Handling user input and events in a browser environment.
- Structuring code for readability and maintainability.
- Basic styling with CSS to enhance user experience.🎮 **Tic-Tac-Toe Game**

A simple yet interactive Tic-Tac-Toe game built using **HTML**, **CSS**, and **JavaScript**. Playable in your browser with a clean interface and real-time win/draw detection.

---

## ✨ Features

- Two-player game (X and O)
- Hover effect to show whose turn it is
- Win and draw detection with end-game messages
- Responsive grid layout
- Restart game functionality

---


## 🚀 Getting Started

To run the game locally:

1. **Clone or download** this repository.
2. **Open** `index.html` in any web browser.
3. **Play and enjoy!**

_No build tools or installations required._

---

## 🕹️ How to Play

- Players take turns clicking on empty squares.
- The first player to get three in a row (horizontally, vertically, or diagonally) wins.
- If all squares are filled and no player has three in a row, the game ends in a draw.
- Click the "Restart" button to play again.

---

## 🖥️ Preview

![Tic-Tac-Toe Screenshot](./screenshot/Screenshot%202025-07-25%20125154.png)
![Winning Screenshot](./screenshot/Screenshot%202025-07-25%20125206.png)

---

## 📘 What I Learned

This project helped me learn and apply several new concepts in CSS and JavaScript:

- `::before` and `::after`: Used to draw the "X" and "O" marks dynamically without images or extra HTML.
- `.cell:first-child`, `.cell:nth-child(3n + 1)`, etc.: CSS selectors for precise grid styling.
- `:root` and CSS variables: For reusable values like `--cell-size` and `--mark-size`.
- **CSS Grid layout**: To create a responsive 3x3 board.
- **Class toggling in JavaScript**: For dynamic UI states (hover effects, game results).
- **DOM manipulation**: Updating the game board and messages in real time.
- **Event handling**: Managing user clicks and game restarts.
- **Structuring code**: For readability and maintainability.

---

## 🔧 How It Works

- The 3x3 grid is created using `div.cell` elements.
- **JavaScript** dynamically handles:
  - Player turns (X and O)
  - Win condition checking using index combinations
  - Hover preview using CSS classes
  - Restart functionality
- **CSS** creates the visual representation of Xs and Os using pseudo-elements.

---

## 📌 Technologies Used

- **HTML5** – for game structure
- **CSS3** – for layout and effects
- **JavaScript (Vanilla)** – for all game logic

---

## 🧠 Concepts Demonstrated

- DOM manipulation
- Event handling
- CSS Grid layout
- Conditional rendering
- Responsive UI

---

## 📜 License

This project is licensed under the MIT License.
Made with the help of [Build Tic Tac Toe With JavaScript - Tutorial](https://youtu.be/Y-GkMjUZsmM?si=veKdKSPQ5YJPgV-V)