# The Fisherman's — Homepage Mockup

Design concept for The Fisherman's Restaurant & Bar (San Clemente Pier). Single self-contained file — no build step, no dependencies. Open `index.html` in any browser.

Fonts (Google Fonts): **Pacifico** (script headlines, matches their "The Oyster Bar" brush script) + **Itim** (upright marker body, matches their Noteworthy-style text). To go back to the upscale serif look: swap the Google Fonts link and the `--serif`/`--sans` variables to Cormorant Garamond + Jost, and remove the "handwritten font adjustments" CSS block.

## What's in it

- Cinematic hero with ken-burns motion, staggered text reveal, animated canvas wave divider
- **Live sunset engine** — real NOAA solar math for San Clemente's coordinates (33.4264, -117.612). Sunset time, live countdown, and happy-hour status (M–F 4–7pm PT) all compute client-side, accurate to ~2 min. No API needed.
- Live pier clock (America/Los_Angeles) + auto-dated "Today's Catch" fresh board
- Story section with parallax collage, rotating "Since 1981" badge, animated counters (45 yrs / 68 awards)
- Timeline (1979 pitch → today)
- 5-tab interactive menu showcase (Breakfast / Lunch / Dinner / Oyster Bar / Happy Hour)
- Drag-to-scroll gallery, auto-rotating testimonials, magnetic buttons, scroll-progress bar, film-grain overlay, scroll-triggered reveals throughout
- The Galley, Private Events / Gift Cards / VIP trio, reserve band, footer with live Google Maps embed
- Fully responsive; mobile menu with circular clip-path reveal

## Swap before client handoff

- Images are Unsplash placeholders — swap for real photography of the restaurant/pier (search `images.unsplash.com` to find them all)
- Menu prices are plausible samples, not real
- Reserve/menu links are `#` stubs — point at Toast/OpenTable when real
- Footer carries a "Design concept — not affiliated" note; remove when appropriate

## Facts used (real)

Est. 1981, first restaurant on the San Clemente Pier, founder Hal Griffith, 68 "Best of San Clemente" awards, 611 Avenida Victoria, (949) 498-6390, sunset happy hour M–F 4–7pm, The Galley weekends.
