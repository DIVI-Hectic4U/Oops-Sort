# 🎮 Switch Sort

**Switch Sort** is a fast-paced arcade puzzle game where you drag red and blue balls from a conveyor into their bins. 
But beware — controls and bins randomly switch mid-game, forcing you to adapt quickly or lose lives. 
Simple to play, tough to master.

---

## 📥 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/DIVI-Hectic4U/switch-sort.git
   ```
2. Open the project in **Unity (2021.3 LTS or later recommended)**.
3. Press ▶️ Play in the Editor or build for your target platform.

---

## 🕹️ How to Play

- **LMB** → Red ball (default)  
- **RMB** → Blue ball (default)  
- Drag balls from the conveyor → drop them into bins.  
- **Switch Controls**: Buttons swap (LMB = Blue, RMB = Red).  
- **Switch Bins**: Bin colors swap (Red bin takes Blue balls, Blue bin takes Red balls).  
- Score points for correct sorting.  
- Correct moves **add time**, wrong moves **cost lives (3 total)**.  
- Game ends when timer reaches 0 or lives = 0.

---

## ✨ Features

- ✅ Simple drag & drop gameplay  
- 🔄 Random Switch Controls and Switch Bins events  
- ⏱️ Timer + Lives system for challenge  
- 🏆 High score saving for replayability  
- 🎵 Sound effects and visual feedback  
- 🚀 Increasing speed for difficulty scaling  

---

## 📸 Screenshots

*(Add screenshots/gifs here to show gameplay)*

---

## 🗂️ Project Structure

```
Assets/
 ┣ Scripts/        # Game logic scripts
 ┣ Prefabs/        # Ball, Conveyor, Bin prefabs
 ┣ UI/             # Score, Timer, Lives display
 ┗ Scenes/         # Main scene
```

---

## 🛠️ Build Instructions

1. In Unity, go to **File → Build Settings**.  
2. Select your target platform (PC/WebGL recommended).  
3. Click **Build and Run**.  

---

## 📜 License

This project is licensed under the MIT License.  
See [LICENSE](LICENSE) for details.  
