<div align="center">

```
 ███╗   ███╗██╗███╗   ██╗██╗    ██████╗  ██████╗ ██████╗ ████████╗ █████╗ ██╗
 ████╗ ████║██║████╗  ██║██║    ██╔══██╗██╔═══██╗██╔══██╗╚══██╔══╝██╔══██╗██║
 ██╔████╔██║██║██╔██╗ ██║██║    ██████╔╝██║   ██║██████╔╝   ██║   ███████║██║
 ██║╚██╔╝██║██║██║╚██╗██║██║    ██╔═══╝ ██║   ██║██╔══██╗   ██║   ██╔══██║██║
 ██║ ╚═╝ ██║██║██║ ╚████║██║    ██║     ╚██████╔╝██║  ██║   ██║   ██║  ██║███████╗
```

### 🕹️ A pocket arcade, built with love — no quarters needed.

[![GitHub Pages](https://img.shields.io/badge/LIVE%20NOW-GitHub%20Pages-brightgreen?style=for-the-badge&logo=github&logoColor=white)](https://fernandoznga.github.io/games4vicky/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=for-the-badge)](/)
[![Mobile Ready](https://img.shields.io/badge/mobile-ready-blue?style=for-the-badge&logo=apple&logoColor=white)](/)

</div>

---

<div align="center">

## ⚡ INSERT COIN TO START ⚡

**[🎮 &nbsp; PLAY NOW &nbsp; 🎮](https://fernandoznga.github.io/games4vicky/)**

*No install. No sign-up. No ads. Just games.*

</div>

---

## 🗺️ STAGE SELECT

> *Four games. One portal. Infinite procrastination.*

| # | Game | Genre | Difficulty | Players |
|---|------|-------|------------|---------|
| 🧮 | **Calculator** | Utility / Brain Teaser | ⭐ Chill | 1 |
| 🐍 | **Number Snake** | Arcade | ⭐⭐ Medium | 1 |
| ✕○ | **Tic Tac Toe** | Strategy | ⭐ Chill | 2 |
| 🐔 | **Chicken Crossing** | Arcade / Reflex | ⭐⭐⭐ Sweaty | 1 |

---

## 📖 GAME MANUALS

<details>
<summary><b>🧮 Calculator — "It's giving main character energy"</b></summary>

<br>

You asked for a calculator. We delivered a **sleek, dark-themed calculator** that slaps harder than it has any right to.

- Full arithmetic: `+` `−` `×` `÷`
- Expression preview on the display
- Chained operations
- Keyboard support (because clicking is for casuals)

**Pro tip:** Hit `Escape` to clear, `Backspace` to undo a digit. You're welcome.

</details>

<details>
<summary><b>🐍 Number Snake — "Just one more round..." (Famous last words)</b></summary>

<br>

Classic snake with a twist — the food has **numbers** on it, and eating them adds that value to your score. A `9` is worth more than a `1`. Choose wisely.

- Grows with every bite 🍽️
- Walls and self-collision = instant regret
- Best score saved to `localStorage` (survives browser restarts, unlike your dignity)
- Smooth gradient snake body because aesthetics matter

**Pro tip:** The snake can't reverse direction. Plan ahead or perish.

</details>

<details>
<summary><b>✕ Tic Tac Toe ○ — "Friendship Destroyer™"</b></summary>

<br>

Pass-and-play Tic Tac Toe for two players sharing one screen. A **pass screen** hides each player's move, keeping the suspense alive (we're watching you, sneaky-peekers).

- Running score tracker across rounds
- Winning cells pulse green ✨
- Reset scores button for when things get too real
- Animated pass screen between turns

**Pro tip:** Center square. Always. That's the whole tip.

</details>

<details>
<summary><b>🐔 Chicken Crossing — "Why did the chicken cross the road?"</b></summary>

<br>

To get to the **🏁 FINISH LINE**, obviously. But there's a highway of absolute chaos between the chicken and glory.

- 8 lanes of traffic going both ways at different speeds
- Move **one step at a time** — up, down, left, right
- 3 lives. Lose them all = game over. Brutal.
- Best score saved locally
- Mobile D-pad overlay for on-the-go anxiety

**Pro tip:** Diagonal thinking doesn't exist here. Pick your lane, commit, and pray.

</details>

---

## 🎮 CONTROLS

Every game supports **keyboard**, **mouse/tap**, and **on-screen D-pad** (mobile).

| Action | Keyboard | Mobile |
|--------|----------|--------|
| Move Up | `↑` or `W` | ▲ D-pad |
| Move Down | `↓` or `S` | ▼ D-pad |
| Move Left | `←` or `A` | ◀ D-pad |
| Move Right | `→` or `D` | ▶ D-pad |
| Calculator input | Number keys, `Enter`, `Esc`, `Backspace` | Tap buttons |

> 🗒️ D-pad is a **translucent overlay** on top of the game canvas — it stays out of the way on desktop, but becomes your best friend on mobile.

---

## 🏗️ PROJECT STRUCTURE

```
games4vicky/
├── index.html        ← 🏠 The portal / game select screen
├── calculator.html   ← 🧮 Calculator
├── snake.html        ← 🐍 Number Snake
├── tictactoe.html    ← ✕○ Tic Tac Toe
└── chicken.html      ← 🐔 Chicken Crossing
```

**Zero build steps. Zero frameworks. Zero nonsense.**
Just open any `.html` file in a browser and go.

---

## 🛠️ TECH STACK

```
HTML5 ████████████████████ 100%  — Structure & canvas games
CSS3  ████████████████████ 100%  — Dark theme, animations, responsive layout
JS    ████████████████████ 100%  — Game logic, requestAnimationFrame loops
Deps  ░░░░░░░░░░░░░░░░░░░░   0%  — (none. zero. zip. nada.)
```

Every game is a **single self-contained HTML file**. No bundlers, no node_modules, no existential dread.

---

## 🚀 RUN LOCALLY

```bash
# Option 1 — Just open it (seriously, that's it)
open index.html

# Option 2 — Serve it locally if you want proper URLs
npx serve .
# or
python -m http.server 8080
```

---

## 🌐 DEPLOYMENT

This project auto-deploys to **GitHub Pages** from the `main` branch.

Every `git push` → live in seconds. No CI needed. Pure HTML magic.

🔗 **Live URL:** https://fernandoznga.github.io/games4vicky/

---

## 🏆 HIGH SCORE BOARD

| Stat | Value |
|------|-------|
| 📦 Total files | 5 HTML files |
| 🧩 Games | 4 |
| 📏 Avg file size | ~10 KB |
| 📡 Network requests at runtime | 0 |
| 🍪 Cookies used | 0 |
| 🔐 Data sent to servers | 0 |
| 💾 High scores stored | `localStorage` (your device only) |

---

## 🎨 DESIGN SYSTEM

All games share the same visual DNA:

- **Background:** `#0d1117` — deep space dark
- **Cards/surfaces:** `#161b22` — GitHub-dark inspired
- **Accent — Blue:** `#63b3ed` (Calculator)
- **Accent — Green:** `#68d391` (Snake)
- **Accent — Orange:** `#f6ad55` (Tic Tac Toe)
- **Accent — Yellow:** `#f6e05e` (Chicken Crossing)
- **Font:** `Segoe UI` — clean, system-native

---

<div align="center">

---

*Made with ❤️ and probably too much ☕*

*"Why did the chicken cross the road? To beat her high score."*

</div>
