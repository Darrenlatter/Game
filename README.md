# 🚀 Scout Flyer — HTML Game

A Flappy Bird-style game built in one HTML file, designed for Scout coding evenings.
Play it, then edit the code to make it your own!

---

## 📁 Repo structure

```
your-repo/
├── index.html        ← The game (rename game.html → index.html for GitHub Pages)
├── README.md         ← This file
└── images/           ← Put your sprite images in here!
    ├── player.png
    ├── top-obstacle.png
    ├── bot-obstacle.png
    └── background.png
```

> **Tip:** GitHub Pages serves `index.html` automatically.
> If your file is called `game.html`, rename it to `index.html`.

---

## 🌐 Enabling GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under *Branch*, choose **main** and click **Save**
4. After a minute, your game will be live at:
   `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

---

## 🎨 Adding your own images

1. Create an `images/` folder in your repo
2. Upload your picture files there (`.png`, `.jpg`, `.gif`, `.svg` all work)
3. Open `index.html` and find **SCOUT EDIT ZONE 3**
4. Replace the long `data:image/svg+xml;base64,...` text with the file path:

```js
// Before (built-in sprite):
player: "data:image/svg+xml;base64,PHN2ZyB4...",

// After (your own image):
player: "images/player.png",
```

> ⚠️ **Filenames are case-sensitive on GitHub!**
> `Player.PNG` is NOT the same as `player.png` — use lowercase to be safe.

---

## ⚙️ Things you can change (Edit Zones)

| Zone | What it controls |
|------|-----------------|
| **Zone 1** — CSS Style | Page colours, fonts, button colours |
| **Zone 2** — Page Text | Game title, button label, instructions |
| **Zone 3** — Sprites   | Player image, pipe images, background |
| **Zone 4** — Settings  | Gravity, speed, gap size, difficulty |

### Fun settings to experiment with:

| Setting | Default | Try making it… |
|---------|---------|----------------|
| `gravity` | `0.055` | `0.02` (floaty) or `0.12` (heavy) |
| `boostForce` | `-0.28` | `-0.15` (gentle) or `-0.45` (rocket!) |
| `pipeSpeed` | `-2.2` | `-1.5` (slow) or `-4.0` (fast!) |
| `minGap` / `maxGap` | `120` / `210` | `160` / `260` (easier) or `80` / `120` (hard!) |
| `pipeSpawnEvery` | `145` | `100` (lots of pipes) or `220` (fewer pipes) |

---

## 💡 Ideas for scouts

- 🐦 Change the player to a bird, a Scout logo, or your face!
- 🌲 Use a forest photo as your background
- ⛰️ Replace the pipes with mountains or trees
- 🔊 Can you add a sound effect? (search: *HTML5 Audio play javascript*)
- 🌈 Change all the colours to your troop's colours

---

*Happy coding! — built with HTML, CSS & JavaScript. No libraries needed.*
