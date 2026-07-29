# Bang-Bang

A simple 2D shooting game built with **Python** using **Pygame** and **Pygame Menu**.  
The project was created as a fun way to practice game development concepts such as game loops, collision detection, player movement, enemy AI, scoring, and menu systems.

---

##  Features

-  Smooth player movement
-  Shooting mechanics
-  Enemy spawning
-  Health/Lives system
-  Score tracking
-  Interactive main menu
-  Sound effects and music
---

##  Screenshots

| Menu | Gameplay |
|----------|------|
| <img src="https://github.com/hossein1269/Bang-Bang/assets/104985574/5a3491d8-27ab-41fe-9c5f-569506482238" width="100%"> | <img src="https://github.com/hossein1269/Bang-Bang/assets/104985574/b1c5c647-8744-492b-b3b5-c6f5d9ad981d" width="100%"> |

---

## Built With

- Python 3
- Pygame
- Pygame Menu

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/HosseinMaani/Bang-Bang.git
cd Bang-Bang
```
### 2. Create Environment
```bash
python -m venv .env
.env\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pygame pygame-menu
```

---

## Run the Game

```bash
python main.py
```

## 📂 Project Structure

```text
Bang-Bang/
│
├── README.md
├── requirements.txt
│
└── src/
    ├── main.py
    │
    ├── Assets/
    │   ├── fonts/
    │   │   └── agancy_fb.ttf
    │   │
    │   ├── images/
    │   │   ├── clouds.png
    │   │   ├── Fighter.png
    │   │   └── enemy/
    │   │       ├── 1.png
    │   │       ├── 2.png
    │   │       ├── 3.png
    │   │       ├── 4.png
    │   │       └── 5.png
    │   │
    │   └── sounds/
    │       ├── fire.mp3
    │       ├── fly.mp3
    │       └── menu_music.ogg
    │
    └── Database/
        ├── bangBang.db
        └── GameDatabaseManager.py
```

---

## 🎮 Controls

| Key | Action |
|-----|--------|
| W / A / S / D | Move |
| Space | Shoot |
| ESC | Pause / Menu |

---

## Future Improvements?

- Multiple enemy types
- Boss fights
- Power-ups
- More weapons
- Difficulty levels
- Save & Load game progress
- Leaderboard
- Fullscreen support

---

## 📄 License

This project is open-source and available under the **MIT License**.
