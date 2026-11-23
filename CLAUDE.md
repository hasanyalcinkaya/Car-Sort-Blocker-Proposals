# Game Manager Case Study

This repository holds playable prototypes and pages for a game manager case study.
The owner talks in Turkish; reply in Turkish. Deliverables (pages, write-ups) are in English.

## Structure
- One folder per game. Start a new folder when a task moves to a new game.
  - `car-sort/` – Car Sort blocker proposals: `blocker1/` … `blocker4/` (each an `index.html`)
  - `gecko-out/` – Gecko Out: `learning-level-proposal.html`
- Folder and file names: lowercase, words joined with hyphens, no spaces.

## Publishing
- Pages are served by GitHub Pages from `main`:
  `https://hasanyalcinkaya.github.io/game-manager-case-study/<folder>/<file>`
- Commit and push straight to `main` when the owner asks to publish.
- Moving or renaming a published page breaks its link; ask before doing it.
- For every new published page, offer a QR code for its link as an SVG.

## Prototype style
- Each prototype is a single self-contained HTML file (inline CSS and JS, canvas board, no build step).
- Phone-frame layout: full screen on mobile, a centered phone-sized frame on wide screens.
- Top bar with level info and a restart button; a short proposal title at the bottom
  (e.g. "Learning Level Proposal - Ghost Gecko"); win and fail overlays with a restart button.
- Play the level through headlessly (Playwright) before publishing and check for console errors.
