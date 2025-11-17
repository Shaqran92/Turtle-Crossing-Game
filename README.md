# 🐢 Turtle Crossing Game  

A Python Turtle Graphics mini-game where you guide a turtle safely across a busy road while avoiding moving cars.  
With increasing levels, faster cars, collision detection, and a persistent high-score system — this project recreates the classic arcade-style crossing challenge using clean, modular OOP-based Python code.

---

## 🎮 Features
- 🐢 **Player movement** (forward/backward)  
- 🚗 **Dynamic car generation** with random colors & lanes  
- ⚡ **Increasing difficulty** as levels rise  
- 💥 **Collision detection** with precise hitboxes  
- 🏁 **Finish-line detection & level progression**  
- 🧹 **Auto-removal of off-screen cars** (prevents memory leaks)  
- ⭐ **High Score Tracking** (persists during runtime)  
- 🔁 **Restart system** after game over  
- 🎨 Fully OOP structured: `Player`, `CarManager`, `Scoreboard`

---

## 🗂 Project Structure
📁 Turtle_Crossing_Game
│── main.py
│── player.py
│── car_manager.py
│── scoreboard.py

---

## 🚀 How to Run
1. Install Python  
2. Run the game  
```bash
python main.py
```

Use the keyboard to play:

- ⬆️ Move Up
- ⬇️ Move Down
- SPACE → Restart after Game Over
