# Prompt Compendium Builder

A single-file, offline-first tool for building your own personal archive of AI image/video generation prompts.

**[Try it live](#)** — or just download `index.html` and open it in any browser.

## What it does

- Add prompts through a form: model/tool, a short subject label, category, and the full prompt text
- **Auto-suggest** guesses a category from the prompt text using simple keyword rules — always editable
- Everything saves automatically to your browser's local storage on your device — no account, no server, no sign-up
- Search and filter by model or category
- A sidebar table of contents groups everything by category, with jump-to-entry links
- **Export** your compendium as a `.json` backup any time; **Import** it back in (replace or merge)
- **Print / Save PDF** for a clean printable copy via your browser's print dialog
- One-click **Copy** on every prompt card

## Why local storage instead of a database

This is meant to be usable by anyone with zero setup: no account, no backend, no cost to run, and no data leaves your machine unless you explicitly export and share the file yourself. The trade-off is that your data lives in one browser on one device — use Export regularly if you want a backup or want to move to another machine.

## Running it

There's nothing to build or install. Either:
- Open `index.html` directly (double-click it), or
- Serve the folder with any static file server, e.g. `python3 -m http.server` then visit `http://localhost:8000`

## License

MIT — do whatever you want with it.
