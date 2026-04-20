# DESIGN — Portfolio Reel

## Style
"Dark Showcase" — ultra-dark canvas, each website is the hero. The wrapper never competes.
Inspired by high-end agency showreels and cinematic product trailers.

## Colors
- Background: `#080808` (near-black, warm undertone)
- Foreground: `#f0ece6` (warm white)
- Accent gold: `#c4a35a`
- Muted label: `#6b6560`
- Subtle label: `#3a3a3a`

## Typography
- `Bebas Neue` — ALL CAPS, cinematic. Headlines, site names, counters.
- `Inter` (300–400) — thin and precise. Category labels, UI text, CTA.

## Motion Rules
- Entrances: `expo.out` for big type, `power3.out` for frames, `power2.out` for labels
- Hold: subtle slow zoom on screenshots (scale 1→1.05 over scene duration)
- Timing: 0.5–0.65s for main elements, staggered 0.15–0.2s apart
- Ambient: breathing gold glows (`sine.inOut`, yoyo)

## Transitions
Brief black flash (0.3s total) between scenes — dark, cinematic, cleans the palette.

## What NOT to Do
- No bright wrapper background — sites must pop against the dark
- No gradient text on the wrapper level
- No more than 2 animated elements simultaneously in the wrapper
- No border or drop shadow on the text labels
