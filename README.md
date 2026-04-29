# COOP

Concept redesign for [coop.meme](https://www.coop.meme) — a community-first, one-cycle-one-token memecoin launchpad on Solana.

## What it is

A self-contained static prototype of a redesigned launchpad UI. Single `index.html`, no build step.

## Design direction

**Functional neo-brutalism** — chunky borders, hard drop shadows, monospaced numbers on the brand surfaces (cycle hero, voting cards, CTAs); calmer treatment inside the data-dense trade pane (chart, order table, buy form).

Palette and typography are sourced directly from the coop.meme brand:

- Background `#FDF6E8` cream · text `#1E1712` warm brown-black
- Accent `#F4C455` (chicken body) · `#E8A63C` (shadow) · `#C87C15` (outline) · `#D64A2E` (comb / sell)
- Phase colors: `#D4C5A0` fairlaunch · `#E6D4A8` bonding · `#F4B5A8` graduating
- Display font: Tektur · body: Space Grotesk · numbers: JetBrains Mono

## Surfaces

| Tab          | Purpose                                                                 |
| ------------ | ----------------------------------------------------------------------- |
| **THE COOP** | Cycle hub — phase, countdown, winning identity, airdrop pool, activity  |
| **VOTE**     | Three-column voting on name / ticker / logo · weighted by holdings      |
| **TRADE**    | Chart + time-progress phase bar + buy/sell pane + trades / holders      |
| **ME**       | Bag, votes cast, estimated airdrop share, cycle history                 |

## Run locally

```sh
open index.html
```

That's it.
