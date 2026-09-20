# Night Night

An aspen tree sprouts, grows, turns gold and lets its leaves fall under a slowly
turning sky of stars. A wise old owl and a smaller white owl settle in the
branches. Tap the owl for night advice from the stars. Left alone, the two owls
hop up the tree, share a kiss, and the night fades to spinning stars, a galaxy,
two blinking owl eyes and a heart made of stars before the words "Night Night"
appear and it all begins again.

A single self-contained `index.html` — canvas animation, no build step, no
dependencies beyond `serve` for hosting.

## Deploying on Railway

1. Push this repo to GitHub.
2. In Railway: **New Project → Deploy from GitHub repo** → select this repo.
3. Railway auto-detects Node and runs `npm start`, which serves `index.html` via `serve`.
4. Go to **Settings → Networking → Generate Domain** to get a public URL.
5. Every push to the main branch auto-redeploys.
