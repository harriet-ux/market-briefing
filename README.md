# Muse — styled from what you own

A mobile-first styling app. Pick a piece from your wardrobe each morning and see
**four ways to wear it**, laid out on an effort dial from *Effortless* to *Glam*,
built only from clothes, shoes and jewellery you already own. Snap something new
to check what it goes with before you buy.

## This prototype

`index.html` is a self-contained, offline mobile web app — open it in a browser
(add to your phone's home screen for the full app feel). No build, no setup.

- **Onboarding** — name, body shape, lifestyle, colour leanings, and inspiration
  photos (Pinterest screenshots + outfits you've loved).
- **Morning** — pick a top, bottom or dress → four looks, casual → glam, each with
  a one-line "why this works". Flip the **occasion** (Everyday / Work / Weekend /
  Date / Event) to re-style on the fly.
- **Wardrobe** — your full collection, filterable by category. Ships with a sample
  wardrobe so the flow works immediately.
- **Add / fitting room** — photograph or hand-add a new piece and see what it
  pairs with before adding it to your collection.

Your wardrobe and profile persist locally (localStorage). "Reset everything" in
your profile restores the sample.

## How the styling works

The prototype uses a rule-based styling engine (colour harmony + a formality
scale shifted by effort level and occasion) so everything runs with zero setup.
It's structured so a Claude vision + reasoning brain can slot straight in later —
reading your photos to tag each piece, learning your aesthetic from your inspo,
and reasoning out richer, more personal looks.

## Roadmap ideas

- Claude vision tagging of uploaded garment photos (auto colour / category / formality)
- Style DNA extracted from Pinterest board screenshots
- Live Pinterest board sync
- "Wear log" so it learns what you actually reach for
- Packing / capsule mode for trips
