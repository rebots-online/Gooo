# Gooo: Game of Gooo (Decentralized Distributed Hashtable Edition)

### Welcome to Gooo

A modern web-based implementation of the classic board game **Go** (also known as *Weiqi* or *Baduk*), built for the browser with a sleek, responsive UI. This edition explores decentralized and distributed concepts, designed for both local play and (future) peer-to-peer matchups.

> **Note:** This project is in early development. P2P features are currently stubbed and do not perform real network communication.

---

### Features

- **Play Go in Your Browser:** Intuitive UI with support for 9x9, 13x13, and 19x19 boards.
- **Versus AI (PvC):** Challenge a built-in AI opponent (easy mode; more difficulty levels planned).
- **Local PvP:** Two players can share the device and alternate turns.
- **P2P (Planned):** UI support for Peer-to-Peer games via invite code and the Jami protocol. *(Currently a UI stub; no networking.)*
- **Tutorial & About:** Built-in modal guides for new players and project information.
- **Save & Load Games:** Save your progress locally and resume games later.
- **Customizable Settings:** Adjust Komi and AI difficulty. All settings are saved to your browser.
- **Responsive Design:** Works on desktop and mobile, dark-mode themed with TailwindCSS.
- **Hints (AI Only):** Get move suggestions when playing against the AI.
- **Game Scoring & Territory Calculation:** Includes territory, capture, and Komi scoring.
- **In-Game Controls Tray:** Quick access to pass, resign, toggle coordinates, and more.

---

## Getting Started

```bash
# 1. Clone or Download
git clone https://github.com/rebots-online/Gooo.git
cd Gooo

# 2. Open in Browser
# This project is static HTML/JS/CSS. Simply open index.html in your browser:

# Option 1: Double-click index.html

# Option 2 (recommended): Run a local server for best file handling
python -m http.server

# Then visit:
http://localhost:8000
```

---

## Gameplay

- **Start a Game:** Choose board size and mode (Player vs AI or Player vs Player).
- **Making Moves:** Click on empty intersections to place your stone.
- **Pass/Resign:** Use in-game controls to pass your turn or resign.
- **Score:** Scores are automatically calculated at game end (including Komi and captures).
- **Hints:** If stuck vs AI, ask for a hint.
- **Save/Load:** Use the sidebar to save or load your current game.
- **Settings:** Adjust Komi, AI difficulty, and board display options.

### P2P Play (Planned/Stub)

- **Host Game:** Generates a three-word invite key (stub only).
- **Join Game:** Enter an invite key to simulate joining (stub only).
- **Jami Integration:** Contains placeholders for future P2P via the Jami protocol. No actual networking yet.

---

## Project Structure

```
index.html          # Main application (self-contained HTML, JS, CSS)
assets/             # (Optional) Place for images, icons, or future assets
README.md           # This file
```

---

## Technical Highlights

- HTML5 + TailwindCSS for layout and styling.
- Pure JavaScript – No frameworks; all logic runs in-browser and self-contained.
- LocalStorage for saved games and settings.
- Responsive UI – Optimized for all device sizes.
- Accessible Controls – Keyboard and screen-reader friendly modals and buttons.
- Expandable – Designed for future distributed/P2P Go gameplay.

---

## Roadmap

- Full P2P multiplayer via Jami or similar protocol.
- Stronger AI (more difficulty levels, smarter heuristics).
- Game analysis and review tools.
- User profiles and persistent cloud saves.
- Enhanced accessibility and theming.

---

## About

**Gooo** is a project by Robin Cheung, MBA to explore *serverless*, decentralized, distributed, and user-friendly implementations of classic games. Contributions and feedback are welcome!

---

## License

This project is proprietary-licensed; it uses certain open-source licensed helper modules. See LICENSE for details.

---

## Acknowledgments

- Inspired by the timeless strategy game **Go**.
- Uses TailwindCSS for rapid styling.
- P2P vision inspired by Jami.

---

## Contributing

Pull requests, issues, and suggestions are encouraged! Please open an issue or PR to get involved.

---

**Enjoy playing Go in your browser!**
