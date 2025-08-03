# 🎲 Dice Roller Web App

This is a simple and interactive **Dice Roller** web application built with **HTML**, **CSS**, and **JavaScript**.

## 🚀 Features

- Enter how many dice you want to roll.
- Click the **"Roll Dice"** button.
- Instantly see:
  - The result of each die roll (e.g., 3, 5, 6)
  - Dice images matching the rolled numbers

## 🧠 How It Works

- When you click the **Roll Dice** button:
  - A random number from 1 to 6 is generated for each die.
  - Each number is displayed along with the corresponding image.
- Dice images are loaded from the `/dice/` folder and should be named `1.png`, `2.png`, ..., `6.png`.

## 🗂️ File Structure

DiceRoller/
├── index.html         # Main HTML file
├── diceRoll.css       # CSS file 
├── diceRoll.js        # JavaScript logic
└── dice/
    ├── 1.png
    ├── 2.png
    ├── 3.png
    ├── 4.png
    ├── 5.png
    └── 6.png





## 📦 Setup

1. Clone or download this repo.
2. Make sure the `/dice/` folder contains all 6 dice face images named exactly `1.png` to `6.png`.
3. Open `index.html` in your browser and start rolling!

## ✅ Tech Used

- HTML5
- CSS3
- JavaScript (DOM Manipulation, Math.random)
