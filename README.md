# ShopBot HQ - Retro AI Agent Dashboard

A premium, interactive retro-game styled monitor dashboard for Shopee Affiliate automation agents. Designed as a unified single-page interface with a responsive layout, neon glowing panels, simulated CRT scanline overlays, smooth waddling character physics, and real-time communication logging.

![ShopBot HQ Preview](screenshot-placeholder.png)

## 🎨 Art Direction & Design

- **Background Scene**: High-fidelity pixel-art office landscape ([image1.png](image1.png)) with a defined, bounded center wooden floor zone where characters walk.
- **Characters**: 7 AI agent sprites extracted from the chibi character sheet ([image2.png](image2.png)) and pre-sliced into individual transparent PNGs. Animate on-screen with custom keyframe animations:
  1. **Supervisor** (Leader) — yellow waddle, monitors telemetry.
  2. **Product Finder** (Searcher) — green waddle, scrapes product feeds.
  3. **Clip Selector** (Curator) — purple waddle, cuts portrait video segments.
  4. **Video Maker** (Creator) — pink waddle, renders overlays.
  5. **Caption Writer** (Wordsmith) — cyan waddle, drafts viral hashtags.
  6. **Post Agent** (Publisher) — magenta waddle, publishes assets to TikTok.
  7. **Analytics Agent** (Strategist) — emerald green waddle, calculates conversion stats.
- **Dashboard UI**: Panels designed to match [image3.png](image3.png) with glassmorphism, customizable neon borders (cyan, magenta, green, purple glows), macOS-style pixelated dot controls, and monospace Google Fonts (`Press Start 2P`, `Share Tech Mono`).

## ⚙️ Features

- **Smooth Walking Physics**: Continuous horizontal walk loops with screen border bounds checks and automatic waddle rotation flips.
- **Agent Interactivity**: Hovering pauses agents and triggers a speech bubble detailing their current tasks. Clicking an agent cycles their state (Active, Idle, Error).
- **Communication Logging**: Sequence of automatic dialog bubbles mapping affiliate progress, auto-logged to a scrolling Team Chat Feed.
- **Simulated SaaS Metrics**: Daily revenue, clicks, and published post counters fluctuate dynamically, alongside a real-time updating SVG performance CTR graph.
- **Terminal input command line**: Enter instructions directly to bots (e.g. `status`, `active`, `halt`, `clear`) and receive interactive replies from the Supervisor.
- **Asset reference inspector**: An inline retro modal displaying the background environment, sprites sheet, and visual mockups.
- **Mobile optimization**: Panels collapse into a bottom action dock, widening the walkable screen space for characters on viewports under 768px.

## 🚀 Setup & Launch

1. Clone or download this project.
2. Ensure the following assets are present in the directory:
   - `index.html` (The dashboard application code)
   - `image1.png` (Background environment)
   - `image2.png` (Spritesheet source)
   - `image3.png` (UI styling template)
   - `char_supervisor.png`, `char_productFinder.png`, etc. (Sliced transparent sprites)
3. Open `index.html` directly in any web browser. No compilation, local server, or frameworks required!

## 📦 Deployment Instructions

Use the following commands to initialize Git, commit the workspace, and push to GitHub:

```bash
git init
git add .
git commit -m "feat: initial ShopBot HQ dashboard with AI agent interactions"
git remote add origin https://github.com/YOUR_USERNAME/shopbot-hq-dashboard.git
git push -u origin main
```
