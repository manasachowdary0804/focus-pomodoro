# 🍅 FOCUS — Pomodoro Timer

A minimal, beautiful Pomodoro timer built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies — just one file that works.

![FOCUS Pomodoro Timer](https://img.shields.io/badge/HTML-Single%20File-orange?style=flat-square&logo=html5)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)

---

## ✨ Features

- **3 Timer Modes** — Focus (25 min), Short Break (5 min), Long Break (15 min)
- **Animated Ring Progress** — Smooth SVG countdown ring with mode-based color theming
- **Auto-switching** — Automatically moves to break after each Pomodoro; long break every 4th session
- **Session Log** — Tracks your completed sessions with timestamps
- **Stats Tracker** — Counts Pomodoros, minutes focused, and your current streak
- **Task Label** — Label what you're working on per session
- **Audio Alert** — Oscillator beep on session complete (no external files needed)
- **Ambient Glow** — Color-reactive background orbs that shift with each mode
- **Zero Dependencies** — Pure HTML/CSS/JS, single file, works offline

---

## 🚀 Live Demo

👉 **[Try it live on GitHub Pages](https://manasachowdary0804.github.io/focus-pomodoro/)**

---

## 📸 Preview

> A dark, minimal interface with a glowing SVG ring timer, mode tabs, session stats, and a task input — all in one page.

---

## 🛠️ Getting Started

### Option 1 — Just open it
```bash
# Clone the repo
git clone https://github.com/manasachowdary0804/focus-pomodoro.git

# Open in your browser
open focus-pomodoro/index.html
```

### Option 2 — Serve locally
```bash
cd focus-pomodoro

# Using Python
python3 -m http.server 3000

# Using Node.js
npx serve .
```

Then open `http://localhost:3000` in your browser.

---

## 📁 Project Structure

```
focus-pomodoro/
├── index.html      # Everything — HTML, CSS, and JS in one file
├── README.md       # You're reading this
└── LICENSE         # MIT License
```

---

## 🎨 Design

| Detail | Choice |
|---|---|
| **Fonts** | Bebas Neue (display), DM Mono (labels), DM Sans (body) |
| **Theme** | Dark — `#0c0c0f` background |
| **Work Color** | Coral red `#e8533a` |
| **Break Color** | Teal `#4ea8a0` |
| **Long Break** | Purple `#7b6fd4` |
| **Animations** | CSS transitions + SVG stroke-dashoffset |

---

## 🧠 How the Pomodoro Technique Works

1. Pick a task to work on
2. Set the timer for **25 minutes** and focus completely
3. When it rings, take a **5-minute break**
4. Every **4 Pomodoros**, take a **15-minute long break**
5. Repeat — and watch your productivity soar 🚀

---

## 🤝 Contributing

Found a bug or have an idea? Feel free to open an issue or submit a PR.

1. Fork this repo
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

MIT © [Manasa](https://github.com/manasachowdary0804)

---

<p align="center">Built with ❤️ and too much coffee</p>
