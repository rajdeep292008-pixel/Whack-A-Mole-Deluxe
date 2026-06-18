# Whack-A-Mole-Deluxe

---

Whack-A-Mole Deluxe is a high-performance, single-file arcade game built using pure HTML5, CSS3, and ES6+ JavaScript. Designed for speed, responsiveness, and addictive gameplay, it offers a premium arcade experience without the need for external frameworks or assets.

## 🚀 Features

---

Procedural Audio: Built-in synthesizer using the Web Audio API for all sound effects.

Persistent Storage: LocalStorage integration to track your lifetime high score.

Adaptive Difficulty: Choose between Easy, Medium, and Hard modes to test your reaction speed.

Responsive Arcade Design: A modern dark-theme UI with neon accents, perfect for both desktop and mobile browsers.

Lightweight Architecture: Zero dependencies—everything is contained within one file for instant deployment.

## 🛠 Tech Stack

---

HTML5: Structured semantic markup for the game board and HUD.

CSS3: Flexbox and Grid for responsive layouts, with smooth animations and transitions.

JavaScript (ES6+): Modular game state management, procedural audio synthesis, and event-driven logic.

## 🎮 How to Play

---

Clone or Download: Save the index.html file to your local machine.

Launch: Open the file in any modern web browser (Chrome, Firefox, Edge, or Safari).

Start: Select your difficulty level to begin the mission.

Objective: Click/tap the moles as they appear. Be fast, stay focused, and climb the leaderboard!

## 🔧 Technical Overview

---

The game logic is encapsulated within the Game object, utilizing a high-efficiency game loop.

Game Manager: Controls state (Playing/Over), score tracking, and grid initialization.

SoundManager: Leverages the AudioContext interface to generate tones in real-time, eliminating the need for bulky .mp3 or .wav files.

StorageManager: Handles localStorage access to ensure your "All-Time Best" score persists across sessions.

---

