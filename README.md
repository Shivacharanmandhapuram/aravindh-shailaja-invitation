# Aravindh & Shailaja — Wedding Invitation

Live: https://aravindh-shailaja-invitation.vercel.app

Phone-first, single-file site (`index.html` + `assets/`). Every push to `main` redeploys the live link on Vercel.

## Updating
- **Names, family, date, venue, WhatsApp number, events:** edit the `CONFIG` block near the bottom of `index.html`.
- **Photos:** add `assets/photo-couple.webp`, `assets/photo-groom.webp`, `assets/photo-bride.webp` — the empty frames fill automatically.
  Event photos are `assets/stock-ev-*.webp` (replace with the same names, or change `photo:` in `CONFIG.events`).
- **Music:** `CONFIG.music` plays "Seetha Kalyana Vaibhogame" (YouTube `r5hSMSpb1Qs`) from 1:37 at volume 20, starting on the guest's first tap — the same as the Pramod–Manisha site. Change `youtube`/`start` to use another song.
- Art prompts used for the illustrations are in `ART-PROMPTS.md` (not published on the site).
