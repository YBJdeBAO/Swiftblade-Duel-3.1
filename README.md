# Swiftblade Duel 3.1

🌐 **Language:** English | [中文](README.zh-CN.md)

A browser-based 1v1 knight duel game built as a single-page HTML5 Canvas experience. Two knights fight in a compact arena with movement, attacks, blocking, dodging, health bars, screen shake, particle effects, and round-by-round win tracking.

Version 3.1 expands the duel with extra event-style mechanics, including a homing sword, a falling heavy head, and a dramatic instant knockout sequence.

## 🚀 Live Demo

https://ybjdebao.github.io/Swiftblade-Duel-3.1/

## ✨ Features

- Single-file static game with no build step.
- PvE mode for practicing against a simple AI opponent.
- PvP mode for two players on the same keyboard.
- Golden Knight and Blue Knight with separate health bars.
- Attack, block, dodge, hit stun, cooldowns, and low-health warning states.
- Victory screen with optional win streak tracking across rematches.
- Canvas-based particles, screen shake, impact feedback, and arcade-style UI.
- Version 3.1 special events: homing sword, rolling heavy head, and instant knockout effects.

## 🎮 Controls

Player 1, Golden Knight:

| Action | Key |
| --- | --- |
| Move left | Q |
| Move right | E |
| Attack | Z |
| Block | X |
| Dodge | C |

Player 2, Blue Knight:

| Action | Key |
| --- | --- |
| Move left | B |
| Move right | M |
| Attack | J |
| Block | K |
| Dodge | L |

Special keys in version 3.1:

| Effect | Key |
| --- | --- |
| Instant knockout sequence | W |
| Homing sword | S |
| Rolling heavy head | D |

## 🕹️ How to Play

1. Open the live demo or serve the repository locally.
2. Choose Practice Match for PvE or Duel Match for PvP.
3. Use movement to manage spacing.
4. Attack when close enough to hit the opponent.
5. Block incoming strikes, or dodge to avoid damage.
6. Win by reducing the opponent's health to zero.

## 🛠️ Local Development

This project is plain HTML, CSS, and JavaScript. No package manager or bundler is required.

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

You can also open `index.html` directly in a browser, although a local server is recommended for a more consistent development workflow.

## 📁 Project Structure

```text
.
├── .github/
│   └── workflows/
│       └── static.yml
├── index.html
├── README.md
└── README.zh-CN.md
```

## 🧩 Technical Notes

- Rendering is handled with the Canvas 2D API.
- Game state, fighters, particles, projectiles, and special events are implemented in vanilla JavaScript.
- Styling uses inline CSS plus Tailwind loaded from a CDN.
- The game is designed for desktop keyboard play.
