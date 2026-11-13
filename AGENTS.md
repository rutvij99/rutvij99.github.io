# rutvij99.github.io (portfolio) — agent guide

## About

Rutvij's personal portfolio, served by GitHub Pages from this repository. It's a static site (HTML, CSS, jQuery and Bootstrap); there is no build step. Last content update: May 2024. It mentions Fission but not newer work (Gravity Well at IGDC, SideQuest, RashRacer, BeybladeRPG).

Status lives in `../../PROJECTS.md` → "Web".

## Layout

- `index.html` — the live page. `f_version.html` and `index1.php` are older variants.
- `css/` (compiled styles), `sass/` (sources), `js/` (`main.js` plus vendored jQuery/Bootstrap plugins), `fonts/`, `images/`, `videos/`.

## Preview

Open `index.html` directly, or run a static server from this folder, for example `python3 -m http.server 8000`.

## Conventions and safety

- **This repository is public** (GitHub Pages on a free plan needs that). Never add private material: client code, unreleased builds, keys, contact details beyond what's already public, or paid assets.
- Commit to `main`; a push publishes the site. `images/portfolio/` is currently untracked; check what it holds before committing it.
- Keep large videos out of git where possible (link to YouTube or the project site instead).
