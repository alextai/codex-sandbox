# Codex Sandbox

Simple demo page that uses anime.js 4.2.0’s `createTimer` helper to display a countdown ticking down from five days. The page is completely static and ready for GitHub Pages.

## Local Preview

- Serve the folder (for example `python3 -m http.server 8000`) and open `http://localhost:8000/`.
- The countdown starts immediately and updates every second until it reaches `00:00:00:00`.

## Deployment

- Push `index.html` to your GitHub repo.
- Enable GitHub Pages in **Settings → Pages**, selecting the branch that holds `index.html` and the root (`/`).
- Within a minute the countdown appears at `https://<username>.github.io/<repo>/`.
