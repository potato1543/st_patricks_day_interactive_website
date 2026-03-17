# ☘️ St. Patrick's Day — Interactive Pot of Gold

A fun, fully interactive St. Patrick's Day web experience built with pure vanilla HTML, CSS, and JavaScript. No frameworks. No libraries. Just one file.

## ✨ Features

- 🌈 **Rainbow over the mountains** — seven-band SVG rainbow arching over layered green Irish mountains
- 🪣 **Interactive pot of gold** — click it and watch coins arc and spill out with physics-style animations
- 🎉 **Three-click surprise** — click the pot three times to trigger the full celebration with confetti and a "Happy St. Patrick's Day!" message
- ☘️ **Animated shamrocks** — swaying shamrock decorations along the ground
- ☁️ **Drifting clouds** — layered cloud formations in the Irish sky
- 📱 **Works on mobile** — tap-friendly, no dependencies

## 🛠️ Built With

- **HTML5** — semantic structure and SVG illustration
- **CSS3** — keyframe animations, CSS custom properties, radial gradients
- **Vanilla JavaScript** — DOM manipulation, dynamic particle system, click state management
- **GitHub Pages** — free static hosting, deployed in minutes

## 🚀 Live Demo

👉 **[Try it here](https://potato1543.github.io/st_patricks_day_interactive_website/)**

## 📁 Project Structure

```
st-patricks-day/
└── index.html    ← the entire project lives here
```

Everything — markup, styles, and scripts — is contained in a single `index.html` file under ~300 lines.

## 🏃 Running Locally

No build step needed. Just clone and open:

```bash
git clone https://github.com/yourusername/st_patricks_day_interactive_website.git
cd st_patricks_day_interactive_website
open index.html
```

Or simply drag `index.html` into any browser.

## 🌐 Deploying to GitHub Pages

1. Push this repo to GitHub (must be **public**)
2. Go to **Settings** → **Pages**
3. Under "Branch" select `main` and folder `/ (root)`
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/st_patricks_day_interactive_website/`

Takes about 60 seconds to go live.

## 🎨 How It Works

### The scene
The background is a CSS linear gradient simulating an Irish twilight sky. Mountains are built from CSS `border` triangles layered at different depths. The rainbow uses SVG `<path>` arcs with semi-transparent strokes for each colour band.

### The pot of gold
The pot is an inline SVG illustration — black cauldron body, gold coin stack, green shamrock band, and cast-iron handles — all drawn in code with no image files.

### The coin animation
Each click spawns a batch of coin `<div>` elements positioned at the pot's center. CSS custom properties (`--cx`, `--cy`, `--cr`) are set per-coin in JavaScript to give each one a unique arc trajectory and rotation. They fade out and are removed from the DOM after landing.

### The three-click payoff
A click counter tracks state. On the third click, a celebration overlay animates in using a cubic-bezier spring curve, and a confetti shower of randomised coloured shapes rains down across the scene.

## 💡 What I Learned / Practiced

- SVG illustration entirely in code
- CSS `@keyframes` with dynamic custom properties set via JavaScript
- DOM particle systems without canvas
- Deploying a static site with GitHub Pages
- Designing for mobile tap interactions

## 📅 Created

March 2026 — built as a St. Patrick's Day mini project to practice frontend animation techniques.

## 📄 License

MIT — free to use, remix, and build on. A credit or star is always appreciated! ⭐

---

*May the luck of the Irish be with your code* ☘️
