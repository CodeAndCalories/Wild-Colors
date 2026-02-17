[README.md](https://github.com/user-attachments/files/25372716/README.md)
# 🖍️ Nature Color Studio

A retro 90s-inspired browser coloring book with procedurally generated nature scenes — inspired by classic CD-ROM coloring games like Crayola Art Studio.

🎨 **[Play it live →](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**

---

## How to Play

1. **Pick a crayon** from the tray at the bottom — it lifts up when selected
2. **Click any enclosed area** on the canvas to flood-fill it with color
3. Hit **🌿 New Picture** to generate a brand-new random scene
4. Hit **🗑️ Clear Colors** to wipe your coloring and start fresh
5. The **white crayon (Eraser)** on the far right removes color from any area

---

## Features

- 🌲 **5 procedurally generated nature scenes** — Forest, Beach, Meadow, Mountain, and Garden
- 🖍️ **24 wax crayon colors + eraser** — styled with pointy tips, wood grain texture, and shiny highlights
- 🪣 **Smooth flood fill** that stays neatly inside the outlines
- ☁️ **Clean coloring book outlines** — every shape is a proper closed region
- ✨ **Retro 90s aesthetic** — scanline overlay, purple neon UI, bouncy loading animation
- 🌐 **Runs entirely in the browser** — no install, no dependencies, no server needed

---

## Running Locally

Just open `index.html` in any modern browser. No build step required.

```
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
open index.html
```

---

## Deploying to GitHub Pages

1. Push `index.html` to the `main` branch of your repo
2. Go to **Settings → Pages**
3. Under *Source*, select **Deploy from a branch** → `main` → `/ (root)`
4. Hit Save — your site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/` within a minute or two

---

## Tech

Pure HTML, CSS, and vanilla JavaScript — no frameworks, no libraries. Scene generation uses a seeded RNG. Coloring uses a queue-based flood fill algorithm on a separate canvas layer.

---

## License

MIT — free to use, remix, and share.
