# Human Capacity

Landing page for **Human Capacity** (Вітальна спроможність українців), an authorial research and cultural project by Khrystyna Kurhanska.

The project collects interviews and intuitive artifacts from guests into a living archive. Part of the collection goes to charity auctions supporting the psychological recovery of veterans through the NGO «ДОЛАДУ».

## Stack

A single static `index.html`: plain HTML, CSS and vanilla JS. No build step, no dependencies. Fonts load from Google Fonts.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

The repository is connected to Vercel. Every push to `main` deploys to production automatically.

## Editing content

All text lives directly in `index.html` (Ukrainian). Contacts are in the `#guest` section near the bottom of the file.
