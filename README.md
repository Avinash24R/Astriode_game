# 🚀 Space Shooter (Asteroids Clone)

A simple 2D space shooter built with **Python + Pygame**.
Control your ship, shoot asteroids, and survive as long as possible.

---

## 🛠️ Setup & Run

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd <your-folder>
```

### 2. Install dependencies (using uv or pip)

Using uv:

```bash
uv sync
```

Or using pip:

```bash
pip install pygame
```

---

### 3. Run the game

```bash
python main.py
```

---

## 🎮 How to Play

| Key          | Action        |
| ------------ | ------------- |
| W            | Move forward  |
| S            | Move backward |
| A            | Rotate left   |
| D            | Rotate right  |
| SPACE        | Shoot         |
| Close Window | Exit game     |

---

## 💥 Gameplay

* You control a spaceship in open space.
* Asteroids spawn from the edges and move across the screen.
* Shoot asteroids to destroy them.
* Large asteroids split into smaller ones.
* If your ship collides with an asteroid → **Game Over**.

---

## 🧠 Features

* Smooth movement using delta time (`dt`)
* Shooting system with cooldown
* Asteroid spawning and splitting
* Collision detection
* Event logging system

---

## 📁 Project Structure

```
.
├── main.py
├── player.py
├── asteroid.py
├── asteroidfield.py
├── shot.py
├── circleshape.py
├── constants.py
├── logger.py
```

---

## 🚀 Future Improvements

* Score system
* Sound effects
* Screen wrapping
* Particle effects
* Enemy AI

---

## 👨‍💻 Author

Built as part of a learning project for game development using Pygame.
