# RETRO INVADERS

A nostalgic, single-file HTML5 arcade shooter built in the spirit of classic 1980s games like *Space Invaders*.

Play it instantly: just open `index.html` in any modern browser.

## Features

- **Classic gameplay** with modern twists
- **Enemy shooting** – the invaders fight back!
- **Emotional characters**:
  - Your ship smiles when you destroy an enemy
  - Enemies smile when their bullets hit you
  - Enemies get sad when their shots miss
  - All remaining enemies celebrate when you lose
- **Progressive waves** – more enemies, faster movement, and tighter formations
- **Authentic chiptune background music** that speeds up with each wave
- **Sound effects** for shooting, hits, and more
- **High score** persistence (saved in your browser)
- Purely client-side – no servers, no installs

## How to Play

### Controls
- **← / →** or **A / D** — Move your ship
- **Space** — Shoot
- **Click** the game area — Also shoots
- **M** — Toggle music on/off
- **R** — Restart after game over

### Objective
Destroy all the invaders before they reach the bottom or shoot you down. Survive as many waves as possible!

## Play Online

### Quickest Way (Recommended for first share)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop the entire `basic-shooting-game` folder (or just the `index.html`)
3. Get an instant public URL you can share!

### Permanent Home - GitHub Pages (Free)
See the section below: **"Deploy to GitHub Pages"**

## Local Play

1. Download or clone this repository
2. Open `index.html` in any browser (Chrome, Edge, Firefox, etc.)
3. Enjoy!

## Technical Details

- Single self-contained `index.html` file (~35KB)
- Built with vanilla HTML5 Canvas + JavaScript
- Web Audio API for music and sound effects
- No external dependencies or frameworks
- Fully responsive controls (keyboard + mouse)

## Project Structure

```
basic-shooting-game/
├── index.html      # The complete game
├── README.md       # This file
```

## Deploy to GitHub Pages (Permanent Free Hosting)

1. Create a new public repository on GitHub:
   - Go to https://github.com/new
   - Name it `retro-invaders` (or whatever you like)
   - Make it **Public**
   - Do **not** initialize with README (we already have one)

2. In your terminal, run these commands:

```bash
cd "C:\Users\kadiy\basic-shooting-game"

git remote add origin https://github.com/kadiyalasriharshakadiyala-wq/Retro-Invaders.git

git push -u origin main
```

3. Enable GitHub Pages:
   - Go to your repo on GitHub → **Settings** → **Pages**
   - Under "Build and deployment":
     - Source: **Deploy from a branch**
     - Branch: `main`
     - Folder: `/ (root)`
   - Click **Save**

4. Wait 1-2 minutes. Your game will be live at:
   ```
   https://kadiyalasriharshakadiyala-wq.github.io/Retro-Invaders
   ```

## Credits

Built as a fun retro project. Feel free to fork, modify, or use the code!

---

**Made with ❤️ for 8-bit nostalgia.**