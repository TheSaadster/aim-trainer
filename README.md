# Aim Trainer

---

**Description:**
This Python script implements a simple aim trainer game using the Pygame library. The aim of the game is to click on targets that appear randomly on the screen while keeping track of hits, misses, and overall accuracy.

---

**Setup:**
Ensure you have Python installed on your system along with the Pygame library. You can install Pygame using pip:

```
pip install pygame
```

---

**How to Play:**
1. Run the script.
```
python main.py
```
2. Targets will appear randomly on the screen.
3. Use your mouse to click on the targets.

---

**Features:**
- Randomly generated targets.
- Timer to keep track of elapsed time.
- Top bar displaying time, speed, hits, and remaining lives.
- End screen displaying game statistics upon completion or failure.

---

**Customization:**
You can customize certain parameters in the script to adjust the gameplay experience:
- `WIDTH` and `HEIGHT`: Adjust the dimensions of the game window.
- `LIVES`: Set the number of lives the player has before the game ends.
- `TARGET_INCREMENT`: Control the frequency of target spawns.
- `MAX_SIZE`, `GROWTH_RATE`, `COLOR`, and `SECOND_COLOR`: Customize the appearance and behavior of the targets.

