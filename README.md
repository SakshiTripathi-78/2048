# 2048 Puzzle Game

A lightweight, browser-based recreation of the classic **2048** puzzle game, built using HTML5, CSS3, and vanilla JavaScript.
You can play this game here : https://sakshitripathi-78.github.io/2048/

## 🚀 Features
* **Smooth Gameplay:** Responsive tile movement using keyboard arrow keys.
* **Logic Engine:** Implements the classic slide-and-merge algorithm to combine tiles.
* **Real-time Scoring:** Tracks your score as you merge tiles to reach higher values.
* **End Game State:** Automated detection when no moves remain, triggering a "Game Over" alert.

## 🛠️ Tech Stack
* **HTML5:** Structures the 4x4 game grid.
* **CSS3:** Handles the grid layout, tile styling, and visual transitions.
* **JavaScript (ES6):** Manages the board state, movement logic, tile generation, and score calculation.

## 🕹️ How to Play
1. **Move:** Use the **Arrow Keys** (Up, Down, Left, Right) on your keyboard to slide all tiles in that direction.
2. **Merge:** When two tiles with the same number touch, they merge into a single tile with the sum of their values.
3. **Generate:** After every move, a new "2" tile will randomly appear on an empty spot.
4. **Goal:** Combine tiles to reach the **2048** tile and achieve the highest score possible!

## 📂 Project Structure
* `index.html`: Main game container and UI.
* `2048.css`: Styling for the board and number-specific tile colors.
* `2048.js`: The game engine, containing logic for sliding, merging, and random tile generation.

## ⚙️ How to Run
1. Ensure you have a local development environment set up (e.g., [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.Liveserver) for VS Code).
2. Open `index.html` in your web browser.

> **Note:** The game logic utilizes a 2D array representation. To improve the user experience, ensure your CSS defines distinct background colors for different tile values (e.g., `.x2`, `.x4`, `.x8`, etc.).

---
*Happy gaming!*
