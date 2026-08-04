# Dude, Let's Hang 🤝

A no-pressure hang group for dads & dudes. Park hangs, gym hangs, game day hangs.

## What's in here

- **`index.html`** — the landing page. The QR code on the cards points here.
- **`cards.html`** — a print-at-home sheet of 10 business cards (US Letter, 3.5" × 2").

## Print the cards

1. Open `cards.html` in a browser (or visit `/cards.html` on the live site).
2. Print at **100% scale** with **background graphics ON**.
3. Cut along the dashed lines. Cardstock is nice, regular paper is fine.
4. Walk around the park. Hand a card to a dude who looks cool.

## Go live (one-time setup)

1. GitHub Pages: repo **Settings → Pages → Source: Deploy from a branch → `main` / root → Save**.
2. In the same Pages settings, set **Custom domain: `dudehangs.com`** and check **Enforce HTTPS**
   (the `CNAME` file in this repo keeps that setting sticky across deploys).
3. At your domain registrar, point `dudehangs.com` at GitHub Pages:
   - Four **A records** on `@`: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - One **CNAME record**: `www` → `draymond-eng.github.io`

The cards' QR codes point at https://dudehangs.com.
