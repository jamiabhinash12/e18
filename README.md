# Abhinash & Soumya — Engagement Invitation

A South Indian temple-style engagement invitation.
**Sunday, 23 · 08 · 2026 · 11:23 AM · Anandayami Function Hall, 80 Feet Road, Srikakulam**

The whole website is a single `index.html` — the couple photo, all artwork
(hand-drawn SVG), styles, and interactions are embedded inside it. No build
step, no dependencies, nothing else to upload.

## Publish with GitHub Pages

1. Keep these two files in the repo: `index.html` and `README.md`.
2. Go to **Settings → Pages**.
3. Under *Build and deployment*, set **Source: Deploy from a branch**,
   **Branch: `main`**, folder **`/ (root)`**, then **Save**.
4. After a minute the invitation is live at
   `https://<your-username>.github.io/<repo-name>/`
   (for example `https://jamiabhinash12.github.io/<repo-name>/`).

Share that link on WhatsApp — it opens straight into the invitation.

## What guests can do

- **Light the two lamps** at the temple entrance (gold sparks, and a blessing
  line appears when both are lit)
- **Ring the temple bells** — a soft synthesized chime, sound only on tap
- **Tap the couple's portrait** to shower flowers, with a running count
- Watch the **live countdown** to the muhurtham time (11:23 AM IST)
- **Get Directions** opens Google Maps to the venue

Kolam dividers draw themselves as you scroll, diyas flicker, jasmine drifts
down, and the mandapam illustration has gentle parallax. Everything respects
`prefers-reduced-motion`.

## Editing details

All text lives in plain HTML inside `index.html` — search for the value you
want to change (names, parents, venue, note). Two values that live in the
script/link at the bottom and top:

- **Countdown target:** search for `2026-08-23T11:23:00+05:30`
- **Maps link:** search for `google.com/maps` — replace the whole `href` with a
  real Google Maps share link (Maps → Share → Copy link) if you have one.

Fonts (Alex Brush, DM Serif Display, Cormorant Garamond) load from Google
Fonts; everything else is self-contained.
