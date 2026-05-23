# Simple Backgammon 🎲

A clean, playable Backgammon game built with HTML, CSS, and vanilla JavaScript. No dependencies, works offline, just open `index.html` in any modern browser.

**New!** Play against a built-in AI opponent.

**Live Demo**: Enable GitHub Pages (Settings → Pages → Source: Deploy from `main` branch) for a shareable link.

## Features
- Authentic 24-point board layout
- Two six-sided dice with roll button
- Click-to-select and click-to-move with legal move highlighting
- Hitting opponent blots (send to bar)
- Bearing off your pieces when all pieces are home
- **Play vs Friend (hotseat)** or **Play vs AI** (Black)
- Win detection and restart

## How to Play
1. Choose mode: **Play vs Friend** or **Play vs AI**
2. Click **Roll Dice**
3. Click one of **your** pieces (White)
4. Click a **green highlighted** legal destination
5. Use both dice when possible
6. Click **End Turn** (AI will then play automatically if in vs AI mode)
7. First to bear off all 15 pieces wins!

**Tip**: You must move in your forward direction. White moves 1→24, Black moves 24→1.

## Rules (Core Backgammon)
- Standard starting layout
- A point with 2+ opponent pieces is blocked
- Landing on a single opponent piece sends it to the bar
- To bear off, all your pieces must be in your home board (points 19-24 for White)

## Project Structure
```
simple-backgammon/
├── README.md
├── index.html      # The full game (Tailwind + Canvas + JS + AI)
```

## Getting Started Locally
```bash
git clone https://github.com/ridertiger/simple-backgammon.git
cd simple-backgammon
# Open index.html directly in your browser
```

## AI Opponent
The AI uses a greedy heuristic:
- Prioritizes hitting your blots
- Prefers bearing off
- Gets pieces off the bar quickly
- Avoids leaving vulnerable single pieces
- Makes solid forward progress

It's challenging but beatable — great for practice!

## Future Ideas
- Stronger AI (minimax + rollout)
- Online multiplayer
- Animations, sounds, and better visuals
- Mobile touch + drag support
- Customizable difficulty

Enjoy rolling those dice! 🎲

---

*Created with GitHub connector + Grok on May 2026*