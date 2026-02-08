🧠 Concept Matching Game

A two-player browser-based memory game built with vanilla HTML, CSS, and JavaScript.
Players flip cards and try to find conceptually related pairs. Each correct match earns a point.

✨ Features

👥 Two-player gameplay

⏱️ Game timer

🔄 Automatic turn switching

🔐 Password-protected entry screen

🎵 Sound effects (click, success, fail)

🎨 3D card flip animations

🏆 Winner announcement or draw result

🎮 How to Play

Open the game and enter the password

Enter names for both players

The game starts after a short countdown

On each turn, a player flips two cards:

✅ If the cards are conceptually related → player scores a point and keeps the turn

❌ If not → cards flip back and the turn switches

When all pairs are matched, the game ends and the winner is announced

🔐 Game Password

The game password is defined inside index.html:

const GAME_PASSWORD = "ramz";


You can change this value to anything you like.

🛠️ Technologies Used

HTML5

CSS3 (Grid layout, animations, 3D transforms)

JavaScript (ES6) – no frameworks or libraries

📁 Project Structure
/
├── index.html
├── click.mp3
├── success.mp3
└── fail.mp3


⚠️ Make sure the audio files are present in the root directory, or sound effects won’t play.

🚀 How to Run

No installation needed.

Just open index.html in any modern web browser (Chrome, Firefox, Edge).

🏁 End Game Logic

The game ends when all card pairs are matched

Scores and total time are displayed

Possible outcomes:

Player 1 wins 🏆

Player 2 wins 🏆

Draw 🤝

📜 License

This project is open-source.
Feel free to use, modify, and expand it for learning or fun 🎉
