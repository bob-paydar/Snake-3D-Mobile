# Snake 3D - Mobile - Ready Web Game
![Screenshot](https://github.com/bob-paydar/Snake-3D-Mobile/blob/main/Screenshot.jpeg)

Snake 3D is a modern, mobile-friendly HTML5/Three.js game featuring responsive 3D graphics, dashcam view, touchscreen controls, and a fully adaptive interface designed to run on both desktop and mobile browsers. The game is optimized for vertical 720×1280 rendering (ideal for YouTube Shorts-style gameplay captures).

## ✅ Features

- **3D gameplay** rendered with Three.js (CDN-based)
- **Fixed 60° perspective** for clear top-view angle
- **Dashcam view** from snake's head for a first-person driving sensation
- **Three selectable speeds:**
  - Easy (slowest)
  - Normal
  - Hard (fast)
- **Responsive controls:**
  - Keyboard (Arrow keys / WASD)
  - On-screen D-pad
  - Swipe gestures (mobile)
- **Auto-fit camera system** that scales view regardless of screen size
- **Mobile-safe UI:**
  - D-pad touch controls
  - Overscroll disabling
  - Safe-area insets support (iPhone)
  - Fullscreen support
- **Wrap mode** (snake wraps at edges)
- **Super-Easy mode** (prevents player from dying)
- **Local high-score tracking** via browser storage
- **720×1280 viewport** inside scalable wrapper for consistent recording

---

## 🚀 Getting Started

### Running locally (recommended)

Start a simple local server:

```bash
python -m http.server 8000
```

Then open in your browser:

```
http://localhost:8000/snake3d_mobile_speed.html
```

### On mobile

1. Connect your mobile device to the same Wi-Fi as your computer.
2. Open your browser and enter:

```
http://<your-computer-ip>:8000/snake3d_mobile_speed.html
```

3. Tap "Play" to start.

---

## 🎮 Controls

### Desktop
- **Arrow keys** — move snake
- **W/A/S/D** — alternate movement
- **P** — pause
- **R** — restart
- **Mouse click** — start game

### Mobile
- **D-pad** — directional control
- **Swipe anywhere** — change direction
- **Tap “Play”** — start game
- **Full-screen button** — immersive mode

---

## ⚙️ Game Modes

### Wrap Mode
- Snake wraps around edges
- Can be toggled ON/OFF during gameplay

### Super-Easy Mode
- Prevents deadly moves
- Ideal for kids

### Speed Selection
Choose from:
- **Easy**
- **Normal**
- **Hard**

Speed affects the snake’s move interval.
You can change speed anytime during play.

---

## 📺 Dashcam Mode

A small 16:9 window shows a **first-person perspective** from the snake head.
This looks like a car dashcam and helps kids understand direction better.

---

## 🧠 Technical Highlights

- Three.js module imported from CDN:
  ```html
  <script type="module">
    import * as THREE from "https://cdn.jsdelivr.net/npm/three@0.160.0/build/three.module.js";
  </script>
  ```
- Auto-fit camera uses projection-based tight-fitting algorithm
- Dual WebGL renderers (main + dashcam)
- Portrait orientation lock on supported devices
- Swipe-based gesture detection

---

## 🛠️ Compatibility

Supports:
- Chrome
- Edge
- Firefox
- Safari (iOS and macOS)

Minimum requirements:
- WebGL-enabled browser
- JavaScript enabled

---

## 🧩 Files

- `snake3d_mobile_speed.html` — Main game file
- `README.md` — Documentation

---

## 📝 License

This game is free to use, modify, and distribute for personal and educational purposes.

---

## 💬 Contact

For feature requests or improvements, feel free to reach out.

Enjoy the game! 🎉
