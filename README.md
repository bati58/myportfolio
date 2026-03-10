# Personal Portfolio

A fast, single‑page portfolio with animated project cards, light/dark theme toggle, and per‑project detail pages.

## Features
- Responsive hero with animated tech icons and internal “Learn more” links.
- Project grid with 3D hover, gradient CTAs, and dedicated detail pages (in `projects/`).
- Light/Dark theme toggle (sun/moon icon) applied to home and detail pages.
- Premium image cards with primary and secondary screenshots per project.
- Static build—no backend required.

## Tech Stack
- HTML5, CSS3 (no JS required for core interactions)
- Inline SVG icon sprites
- Static assets under `public/`

## Structure
- `index.html` – main portfolio page
- `projects/` – detail pages (`youtube.html`, `fenet.html`, `finance.html`, `moviehub.html`, `smilecare.html`, `ecommerce.html`)
- `style.css` – global styles, theme variables, animations
- `public/` – logos, favicons, project images (`*1 / *2 / *3` variants)

## Running Locally
Open `index.html` in your browser or serve the folder:
```bash
npx serve .
```

## Deploying to Vercel (static)
- Framework preset: **Other**
- Build command: leave empty
- Output directory: `.` (root)
- Add domain under **Settings → Domains** and set as primary.

## Updating Project Images
- Hero/detail backgrounds: `public/<project>3.jpg`
- Primary gallery image: `public/<project>.jpg`
- Secondary gallery image: `public/<project>2.jpg`
Replace with your screenshots and keep filenames consistent with the pages.
