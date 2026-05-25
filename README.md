# first-game

A game I designed and built over three days, with Claude as my AI engineering partner.

**Live at**: https://ej-builds.github.io/first-game/

## What this is

A small browser-based game. Open the link above to play it.

Built over three days in June 2026 as part of a work-experience program — designing, building, and shipping something real, using AI-assisted development tools.

## How it was built

The whole thing is one HTML file. It runs in any modern browser, no install needed. The code is in `index.html`.

I used [Claude Code](https://claude.com/product/claude-code) to do the actual writing of the code — I described what I wanted, it wrote it, I tested it, iterated. The way modern software is increasingly being made.

Every change pushed to `main` automatically deploys to the live URL via GitHub Actions. So the version you see at the link above is whatever the latest version is.

## What's in here

- `index.html` — the game itself
- `.github/workflows/deploy.yml` — the deployment pipeline (deploys to GitHub Pages on every push)
- `README.md` — this file
