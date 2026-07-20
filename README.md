# Northwestern AI PM Talk Deck

Live site: https://kiri01-dev.github.io/northwestern-ai-pm/

GitHub repo: https://github.com/kiri01-dev/northwestern-ai-pm

This repo hosts a single self-contained HTML slide deck (`index.html`) via GitHub Pages. The deck is fully self-contained after load — no internet needed once the page is open (verified: no external font/CDN calls, everything reconstructs from an embedded bundle). The GitHub Pages URL itself does need internet to load the first time, same as any website.

## Updating the deck

**Important: `index.html` in this folder is a deployed copy, not the source.** The master file is `../AI PM Talk Deck (standalone).html` (one level up, outside this repo). Always edit the master, then copy it in here — never edit `index.html` directly, or the two will drift out of sync.

1. Edit or re-export the master: `AI PM Talk Deck (standalone).html` in the parent folder.
2. Copy it over `index.html` in this folder.
3. From this folder, run:
   ```
   git add -A
   git commit -m "Update deck"
   git push
   ```
3. GitHub Pages rebuilds automatically, usually live within ~1 minute.

## One-time setup (already done)

- Repo created and pushed under the `kiri01-dev` GitHub account.
- Settings -> Pages -> Source: Deploy from branch -> main -> /(root) -> Save.
