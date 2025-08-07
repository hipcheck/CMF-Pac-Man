# Pac‑Man: City Icons Edition

A single‑file, browser‑playable Pac‑Man clone with a themed board:
- Munich **Olympic Tower**
- **Statue of Liberty**
- Goal tile styled as **Château Marmont**

All graphics are drawn on `<canvas>` in code. No external assets.

## Play locally
Just open `index.html` in any modern browser.

## Deploy options

### 1) GitHub Pages (free)
1. Create a new repo (e.g., `pacman-city-icons`).
2. Upload `index.html` (and this README if you like).
3. In repo settings → **Pages**, set **Source** to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Your site will be live at `https://<your-username>.github.io/pacman-city-icons/`.

### 2) Netlify (free tier)
1. Go to Netlify → New site from Git.
2. Connect your repo (or drag‑and‑drop the `pacman-site.zip` in Netlify Drop).
3. Build command: _none_; Publish directory: `/`.
4. Click **Deploy**.

### 3) Vercel (free tier)
1. Import the repo in Vercel.
2. Framework preset: **Other**; Build command: _none_; Output directory: `/`.
3. Deploy.

### 4) Glitch / Codepen (instant)
- **Glitch**: New project → Import from GitHub → paste repo URL. It will serve `index.html`.
- **CodePen**: Create a new Pen → paste the HTML content into the HTML panel (remove `<!DOCTYPE ...>` if needed).

## Customizing
Open `index.html` and tweak:
- `raw` map at the top of the script to change walls/pellets/goal/landmarks.
- Colors in the `:root` CSS.
- Speeds: `SPEED`, `GHOST_SPEED`, `POWER_TIME`.

Enjoy!