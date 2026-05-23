# Simple Backgammon 🎲

A clean, playable Backgammon game built with HTML, CSS, and vanilla JavaScript. No dependencies, works offline, just open `index.html` in any modern browser.

**Live Demo**: Enable GitHub Pages (Settings → Pages → Source: Deploy from `main` branch) for a shareable link.

## Features
- Authentic 24-point board layout
- Two six-sided dice with roll button
- Click-to-select and click-to-move with legal move highlighting
- Hitting opponent blots (send to bar)
- Bearing off your checkers when all pieces are home
- Hotseat play (two players on one device)
- Win detection and restart

## How to Play
1. Click **Roll Dice** to get your two dice values.
2. Click a point that contains **your** checkers to select it.
3. Valid destinations will highlight in green — click one to move.
4. You can make multiple moves as long as you have dice remaining.
5. When done (or no more moves), click **End Turn** to pass to the other player.
6. First to bear off all 15 pieces wins!

**Tip**: You must move in your forward direction. White moves 1→24, Black moves 24→1.

## Rules (Core Backgammon)
- Standard starting positions (5-3-5-2 setup)
- A point with 2+ opponent pieces is blocked
- Landing exactly on a single opponent piece sends it to the bar
- To bear off, all your pieces must be in your home board (points 19-24 for White, 1-6 for Black)
- Doubles give you four moves of that number

## Project Structure
```
simple-backgammon/
├── README.md
├── index.html      # The full game (Tailwind + Canvas + JS)
├── style.css       # Additional styling
└── script.js       # Game logic
```

## Getting Started Locally
```bash
git clone https://github.com/ridertiger/simple-backgammon.git
cd simple-backgammon
# Open index.html directly in your browser (no server needed)
```

## Future Ideas
- Smart AI opponent
- Online multiplayer (WebSockets / Firebase)
- Animations, sounds, and better visuals
- Mobile touch + drag support
- Full rule enforcement (forced moves, re-roll on no legal moves, etc.)

Enjoy rolling those dice! 🎲

---

*Created with GitHub connector + Grok on May 2026*