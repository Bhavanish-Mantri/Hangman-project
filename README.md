# 🎯 Hangman Game

A classic **Hangman word-guessing game** built using ** HTML, CSS, and JavaScript**.  
The player guesses letters using the keyboard to uncover a hidden word before the hangman figure is fully drawn.

This project demonstrates **DOM manipulation**, **keyboard event handling**, and **game state management** without using any external libraries or frameworks.

---

## 🚀 Live Demo

🎮 Play the game here:  
👉 https://bhavanish-mantri.github.io/Hangman-project/

---

## 🕹️ How to Play

- A random word is selected at the start of the game
- Press any **alphabet key (A–Z)** to guess a letter
- Correct guesses reveal the letter in the word
- Wrong guesses draw parts of the hangman figure
- Repeating the same letter shows a warning notification
- The game ends when:
  - ✅ All letters are guessed correctly (Win)
  - ❌ The hangman figure is fully drawn (Lose)
- Click **Play Again** to restart the game with a new word

---

## ✨ Features

- Random word selection from a predefined word list
- Keyboard-based letter input
- SVG-based hangman drawing
- Wrong letter tracking
- Win / Lose popup messages
- Clean and responsive UI

---

## 🛠️ Technologies Used

- **HTML5** – Game structure
- **CSS3** – Styling and layout
- **JavaScript (ES6)** – Game logic and interactivity

---
## 📂 Project Structure
```
Hangman/
│
├── index.html
├── style.css
├── script.js 
└── README.md
```

---

## 🧠 JavaScript Concepts Used

- DOM manipulation (`getElementById`, `querySelector`)
- Keyboard events (`keydown`)
- Arrays for tracking game state
- Conditional rendering
- Game restart logic

---

## 🔁 Restart Logic

When **Play Again** is clicked:
- All guessed letters are cleared
- The hangman figure is reset
- A new word is randomly selected
- Player input is re-enabled

---

## 🎯 Learning Outcomes

- Understanding event-driven programming
- Managing application state in JavaScript
- Working with SVG graphics dynamically
- Improving UI feedback using popups and notifications

---

## 📌 Future Improvements

- Difficulty levels (Easy / Medium / Hard)
- On-screen keyboard for mobile users
- Larger or dynamic word bank
- Score tracking system
- Animations and sound effects

---

## 📜 License

This project is open-source and free to use for learning and personal projects.

