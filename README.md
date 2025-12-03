# ⚽ KickIt — 3D Football Simulation Game

**KickIt** is a fully-featured 3D football (soccer) simulation game built with **Unity 2022.3.42f1** using the **Universal Render Pipeline (URP)**. Experience realistic gameplay with intelligent AI opponents, multiple game modes, dynamic camera systems, and authentic player mechanics.

---

## 📑 Table of Contents

- [🌟 Key Features](#key-features)
- [🛠️ Tech Stack](#tech-stack)
- [🚀 How to Run the Project](#how-to-run-the-project)
- [📂 Project Structure](#project-structure)
- [📝 Developer Notes](#developer-notes)
- [🤝 Contributing](#contributing)
- [👨‍💻 Developed By](#developed-by)

---

<h2 id="key-features">🌟 Key Features</h2>

### 🎮 Player Abilities & Controls

- **Dynamic Movement:** Smooth third-person controls using WASD/Left Stick with sprint (Shift/L2) and diagonal movement.
- **Action System:** Shoot (Left Click/B), Pass/Steal (Space/A), Tackle (Q/Y), and switch players (E/X).
- **Goalkeeper Mechanics:** Dedicated controls for diving (Arrow Keys) and jumping/catching (Space).
- **Authentic Physics:** Realistic ball movement including spin, bounce, and trajectory calculations.

### 🏆 Modes & AI Environment

- **Versatile Game Modes:** PvP (Local Split), Player vs PC (5 Difficulty levels), and Co-op (2 Players vs PC).
- **Advanced AI:** Opponents utilize attacking strategies, defensive marking, and formation coordination.
- **Formation System:** Choose from tactical setups like 3-4-3, 4-3-3, 4-4-2, and 5-3-2.
- **Referee System:** Automated foul detection, yellow card mechanics, and offside logic.

### 🎥 Visual & Technical Experience

- **Cinematic Cameras:** Dynamic switching between Player Follow, Stadium View, and specialized Replay cams.
- **Replay System:** Instant goal replays with frame-by-frame data recording.
- **Statistics:** Comprehensive tracking of possession, shots, corners, and goals.
- **Visual Polish:** Customizable team colors, URP rendering, and polished player animations.

---

<h2 id="tech-stack">🛠️ Tech Stack</h2>

| Component | Technology |
|-----------|-----------|
| **Engine** | Unity 2022.3.42f1 |
| **Rendering** | Universal Render Pipeline (URP) 14.0.11 |
| **Camera** | Cinemachine 2.10.1 |
| **Input** | Unity Input System 1.7.0 |
| **AI** | Unity AI Navigation 1.1.5 |
| **Architecture** | Component-based with inheritance hierarchy |

---

<h2 id="how-to-run-the-project">🚀 How to Run the Project</h2>

Follow these steps to run **KickIt** on your system using Unity.

### ✅ 1. Prerequisites

Make sure you have:

- [Unity Hub](https://unity.com/download)
- **Unity 2022.3.42f1** (Install via Hub)
- **Universal Render Pipeline (URP)** package
- A computer running Windows, Linux, or macOS

### ✅ 2. Clone the Repository

```bash
git clone https://github.com/Sana-ai-coder/KickIt.git
cd KickIt/KickIt-master
```

### ✅ 3. Open the Project in Unity

1. Launch **Unity Hub**.
2. Click **Open** → Navigate to the `KickIt-master` folder.
3. Unity will automatically import all assets, packages, and URP configurations.

### ✅ 4. Run the Game

1. Open the **Menu** scene located at `Assets/Scenes/Menu.unity`.
2. Click the **Play ▶️** button in the Unity Editor.
3. Alternatively, load `Assets/Scenes/Game.unity` for direct gameplay testing.

### ✅ 5. Build (Optional)

To generate standalone executables:

1. Go to **File → Build Settings**.
2. Select your target platform (Windows/Mac/Linux).
3. Click **Build**.

---

<h2 id="project-structure">📂 Project Structure</h2>

```
KickIt-master/
├── Assets/
│   ├── Ball/             # Football models and physics prefabs
│   ├── Environment/      # Stadium, field, and goal assets
│   ├── Scripts/          # C# Core Logic (Game.cs, Player.cs, AI)
│   ├── Scenes/           # Menu.unity and Game.unity
│   ├── Player/           # 3D models, animations, prefabs
│   ├── Sound/            # Audio effects and commentary
│   ├── UI/               # Menus, HUD, and TextMeshPro assets
│   └── InputSystem/      # Custom input configurations
├── Packages/             # Unity dependencies (URP, Cinemachine)
└── ProjectSettings/      # Engine configuration files
```

---

<h2 id="developer-notes">📝 Developer Notes</h2>

- **Recording System:** A `recording.txt` file is used to store frame-by-frame gameplay data (positions, rotations, animation weights) for the replay system.
- **Extending the Game:** New formations can be added in `Formation.cs`, and AI behaviors can be modified in `AIFieldPlayer.cs`.
- **Assets:** Player meshes and materials are organized by type (hair, body) to allow for customization.
- **Future Roadmap:** Plans include network multiplayer, career mode, and mobile platform support.

---

<h2 id="contributing">🤝 Contributing</h2>

1. **Fork the repository**
2. **Create a new branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m "Add some AmazingFeature"
   ```
4. **Push the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

---

<h2 id="developed-by">👨‍💻 Developed By</h2>

**Sana Girish**

---

**Ready to kick off? Clone, build, and enjoy the beautiful game! ⚽🏆**