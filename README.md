# 🎵 Rhythm Dodge
**A dynamic rhythm-based dodge game built with Pygame!**

**Players control a character to dodge obstacles and survive the beat!**

<img src="https://github.com/haleychang0530/oop-2025-proj-rhythm-dodge/blob/main/assets/images/cover.png" width="600">

## 📂 Project Structure

```Rhythm Dodge/
├── main.py              # Main game loop
├── player.py            # Player class
├── obstacle.py          # Obstacle classes
├── timeline.py          # Timeline and obstacle spawner
├── particle.py          # Particle effects
├── ui.py                # HUD and UI functions
├── start.py             # Start screen
├── tutorial.py          # Tutorial screen
├── main_menu.py         # Main menu
├── win_screen.py        # Victory screen
├── pause.py             # Pause menu
├── gameover.py          # Game over screen
├── levels/
│   ├── level1.json      # Level 1 event timeline
│   ├── level2.json      # Level 2 event timeline
├── assets/
│   ├── music/           # Level music tracks
│   ├── sound_effect/    # Sound effects
│   ├── images/          # Sprites (optional)
├── README.md            # Project documentation
```

## 🗂️ JSON Level Format
Each level has a .json that defines the sequence of events.

*Example:*

```json
[
  {"time": 1000, "type": "obstacle_type", "params": {...}},
  {"time": 2000, "type": "another_obstacle", "params": {...}}
]
```

## 🎮 How to Play

- **Arrow keys** to move.
- **Dash**: (depends on your `Player` implementation)
- Survive by dodging obstacles in sync with the music.
- Press **ESC** to pause the game.
- Reach the end of the song to win!

### 💡 Steps

1. **Enter the tutorial to learn how to play the game.**

<img src="https://github.com/haleychang0530/oop-2025-proj-rhythm-dodge/blob/main/assets/images/tutor.png" width="600">

2. **Select a song to play.**

<img src="https://github.com/haleychang0530/oop-2025-proj-rhythm-dodge/blob/main/assets/images/menu.png" width="600">

3. **Use the arrow keys to move the player left and right.**

4. **Dodge the obstacles that spawn at the top of the screen.**

<img src="https://github.com/haleychang0530/oop-2025-proj-rhythm-dodge/blob/main/assets/images/play.png" width="600">

5. **Player's blood decreases when the player collides with an obstacle.**

6. **The game ends when the player's blood reaches zero.**

<img src="https://github.com/haleychang0530/oop-2025-proj-rhythm-dodge/blob/main/assets/images/over.png" width="600">

## 🏆 To Do / Ideas

✅ Custom levels

✅ Particle effects

✅ Pause & resume

✅ Victory and game over screens

✅ Radial beams visual effect


