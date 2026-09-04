# Tarkov USD conversion rates

A small static tool for Escape from Tarkov: compare flea buy prices against Peacekeeper dollar payouts (₽/$). Lower is better.

## Live site (GitHub Pages)

After you push this repo and enable Pages:

`https://<your-github-username>.github.io/tarkov-usd-rates/`

### Enable Pages

1. Push this repo to GitHub (public).
2. Repo **Settings** → **Pages**.
3. Source: **Deploy from a branch**.
4. Branch: `main` / folder: `/ (root)` → Save.

GitHub will publish in a minute or two.

## Local

Open `index.html` in a browser, or from this folder:

```bash
npx --yes serve .
```

Settings are stored in your browser via `localStorage` (per device / per origin).

## Stack

Single-file HTML/CSS/JS. No build step.
