# 🎮 Simon Game

A fun and interactive **Simon Game** built using **HTML, CSS, JavaScript, and jQuery**. The game challenges players to remember and repeat an increasingly longer sequence of colors.

## 🌐 Live Demo

👉 **[Play Simon Game](https://voggojurohit-crypto.github.io/simons-game/)**

## 📌 About the Project

Simon Game is a memory-based game where the player needs to remember the sequence of colored buttons displayed by the game and reproduce the same sequence.

With every successful round, the sequence becomes longer, making the game progressively more challenging.

## ✨ Features

* 🎮 Interactive gameplay
* 🧠 Memory-based sequence challenge
* 🎨 Four colorful game buttons
* 🔊 Sound effects for each button
* 📈 Progressive difficulty
* ❌ Game-over detection
* 🔄 Automatic sequence generation
* ⌨️ Press any key to start the game
* 📱 Responsive design

## 🛠️ Technologies Used

* **HTML5** – Structure of the game
* **CSS3** – Styling and responsive layout
* **JavaScript** – Game logic and functionality
* **jQuery** – DOM manipulation and event handling
* **Git & GitHub** – Version control and project hosting

## 🎮 How to Play

1. Open the game using the **Live Demo** link.
2. Press any key to start.
3. Watch the game carefully as it highlights a colored button.
4. Click the same colored button.
5. The game will add another color to the sequence.
6. Remember the complete sequence and reproduce it correctly.
7. Continue playing to reach higher levels.
8. If you click the wrong button, the game ends.

## 🗂️ Project Structure

```text
simons-game/
│
├── sounds/
│   ├── blue.mp3
│   ├── green.mp3
│   ├── red.mp3
│   └── yellow.mp3
│
├── game.js
├── index.html
├── styles.css
└── README.md
```

## 🔊 Sound Effects

The game uses individual sound effects for each colored button:

* 🔵 Blue
* 🟢 Green
* 🔴 Red
* 🟡 Yellow

A separate sound is also used for the game-over state.

## 🧠 Game Logic

The game generates a random color sequence.

For every new level:

1. A random button is selected.
2. The selected button is animated and its sound is played.
3. The player repeats the sequence.
4. The player's input is checked against the generated sequence.
5. If the sequence is correct, the next level begins.
6. If the player makes a mistake, the game ends.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/voggojurohit-crypto/simons-game.git
```

### 2. Open the Project

Navigate to the project directory:

```bash
cd simons-game
```

### 3. Run the Game

Open `index.html` in your web browser.

You can also use the **Live Server** extension in VS Code for easier development.

## 💻 Future Improvements

Some possible improvements for future versions:

* 🏆 Add a high-score system
* 💾 Store the highest score using Local Storage
* 🎚️ Add different difficulty levels
* 📱 Improve mobile support
* 🎨 Add additional visual effects
* 🔊 Add sound and volume controls
* ⏸️ Add pause and resume functionality

## 📚 What I Learned

Through this project, I practiced:

* DOM manipulation
* JavaScript event handling
* jQuery selectors and events
* Arrays and sequence management
* Random number generation
* Functions and control flow
* CSS animations
* Audio integration
* Game logic development
* Git and GitHub version control
* Deploying a web project using GitHub Pages

## 👨‍💻 Author

**Rohith Chary**

GitHub:
https://github.com/voggojurohit-crypto

## ⭐ Support

If you like this project, consider giving the repository a ⭐ on GitHub!

---

### 🎮 Have fun and try to beat your highest level! 🚀
