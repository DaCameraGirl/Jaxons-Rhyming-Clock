# Jaxon's Rhyming Clock

A retro arcade clock that helps Jaxon learn his numbers and tell time — with rhymes.

**Live:** https://dacameragirl.github.io/Jaxons-Rhyming-Clock/

## What it does

- Shows the current time on a glowing CRT-style arcade screen.
- Highlights the **hour number** big and bold, with a rhyme to match it (1–12).
- Adds a little extra rhyme on the quarter hours (`:00`, `:15`, `:30`, `:45`).
- Greets Jaxon by time of day (morning / afternoon / evening / night).
- Floating pixel balloons you can **tap to pop** — with an optional arcade blip
  sound (off by default) and a confetti-pixel burst.
- **NEW RHYME** button to hear it again on demand.

## Tech

Single self-contained `index.html` — no build step, no dependencies except two
Google Fonts (Press Start 2P + VT323). Works on phones and respects
`prefers-reduced-motion`.

## Running locally

Just open `index.html` in a browser, or serve the folder:

```powershell
python -m http.server 8080
# then open http://localhost:8080/
```

## Deploy

GitHub Pages serves the `main` branch root directly. A `.nojekyll` file is
included so Pages serves the files as-is (no Jekyll processing). Push to `main`
and the live site updates.
