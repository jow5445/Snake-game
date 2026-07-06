# 🐍 Snake Game

A classic **Snake Game** built with **HTML5 Canvas**, **CSS3**, and **Vanilla JavaScript**. Control the snake using the arrow keys, eat food to grow longer, and avoid colliding with the walls or your own body.

---

## 🎮 Features

- 🐍 Classic Snake gameplay
- 🍎 Randomly spawning food
- 📈 Snake grows after eating food
- ⌨️ Smooth keyboard controls
- 💥 Collision detection with walls
- 🚫 Self-collision detection
- 🎨 Lightweight implementation using HTML5 Canvas
- ⚡ No external libraries or frameworks

---

## 📂 Project Structure

```
snake-game/
│
├── index.html      # Main HTML page
├── snake.css       # Styling
├── snake.js        # Game logic
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/jow5445/Snake-game
```

### 2. Navigate to the project

```bash
cd snake-game
```

### 3. Run the game

Simply open **index.html** in your web browser.

Or use **VS Code Live Server** for the best experience.

---

## 🎯 How to Play

- Press any **Arrow Key** to start moving.
- Eat the **red food** to increase your snake's length.
- Avoid:
  - Running into the walls
  - Running into your own body
- The game ends immediately after a collision.

---

## 🎮 Controls

| Key | Action |
|------|--------|
| ⬆️ Up Arrow | Move Up |
| ⬇️ Down Arrow | Move Down |
| ⬅️ Left Arrow | Move Left |
| ➡️ Right Arrow | Move Right |

---

## 🛠️ Built With

- HTML5
- CSS3
- JavaScript (ES6)
- HTML5 Canvas API

---

## 📖 Game Logic

The game updates **10 times per second** using:

```javascript
setInterval(update, 1000 / 10);
```

Each update performs the following steps:

1. Draw the game board
2. Draw the food
3. Check if food is eaten
4. Move the snake
5. Draw the snake
6. Detect wall collisions
7. Detect self-collisions

---

## 📸 Preview

```
+-------------------------+
|                         |
|         🟩🟩🟩          |
|           🟩            |
|           🍎            |
|                         |
+-------------------------+
```

---

## 💡 Future Improvements

- ⭐ Score counter
- ⭐ High score storage
- ⭐ Restart button
- ⭐ Pause/Resume feature
- ⭐ Mobile touch controls
- ⭐ Sound effects
- ⭐ Difficulty levels
- ⭐ Animated food
- ⭐ Better game over screen
- ⭐ Snake head with eyes
- ⭐ Dark/Light themes

---

## 📄 License

This project is open source and available under the **MIT License**.

---

Made with ❤️ using HTML, CSS, and JavaScript.