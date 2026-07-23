# 🎁 Birthday Surprise

A tiny two-page static site for sending someone a birthday surprise.

- **`index.html`** — the builder. Fill in the birthday person's name, your message,
  and little wishes, pick a theme, and it generates a shareable "magic link".
  All the data is encoded into the link itself — no server or database.
- **`birthday.html`** — the surprise. Typewriter intro, a cake with candles to
  blow out, a Happy Birthday melody (Web Audio), confetti, balloons, and the
  message + wishes revealed as cards.

## Run locally

Just open `index.html` in a browser.

## Hosting

It's a plain static site — deploy the folder as-is to Vercel, Netlify,
GitHub Pages, or any static host. No build step needed.
