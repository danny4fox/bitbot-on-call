# Bitbot On Call

An interactive CI/CD hero for Bitrise: keep your apps alive by fixing stuck pipeline stages with Bitbot, and win 15 days of full access to Bitrise for free.

- `/` is the game (three.js 0.160 from jsDelivr, models as base64 `.glb.txt`)
- `/claim/` is the "15 days off?" claim page with the five fixes, team articles and newsletter signup

Static site with no build step. To preview locally, run `python3 -m http.server 8080` and open http://localhost:8080.

Before launch, replace the placeholders: offer wording, promo code `BITBOT-15`, claim URLs (search for `href="https://bitrise.io/"`) and `NEWSLETTER_ENDPOINT` in `claim/index.html`.

## Fonts
The brand font **TT Norms Pro** is self-hosted from `fonts/` and `claim/fonts/`. Every font stack falls back to **Figtree** (free, Google Fonts). To switch to the free font, delete the `fonts/` folders or the three `@font-face` rules marked `FONT SWITCH`. Before this repo is public, confirm that Bitrise's TT Norms Pro licence covers web embedding and hosting the font files.
