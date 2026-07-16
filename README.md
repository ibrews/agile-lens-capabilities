# Agile Lens — Capabilities Deck

The interactive capabilities deck for **Agile Lens** — the focused, skimmable, deep-linked answer to "what exactly can you do?" Built for prospective clients and partners; every project and press mention links to its source.

**Live:** https://ibrews.github.io/agile-lens-capabilities/
**Framework:** a content fork of [spatial-deck](https://github.com/ibrews/spatial-deck) (fork-per-talk model — framework fixes go upstream, deck content lives here).

15 slides: cover → who we are (interactive two-market split + press wall) → pre-construction (animated Holodeck Anywhere schematic, Four Seasons Lake Austin, Blueprint Immersive workflow race) → live performance (Stage Presence, A Christmas Carol VR) → the stack (hoverable tech constellation) + how engagements work → CTA → constellation map → contact.

## Quickstart

```bash
cd /path/to/agile-lens-capabilities && python3 -m http.server 8745
# open http://localhost:8745 — ← / → to navigate, G for slide grid, N for speaker notes
```

Or just open the live URL above. Verified at 1920×1080 (presentation resolution).

## Things to Try

1. **Walk the deck** — open the [live deck](https://ibrews.github.io/agile-lens-capabilities/) and press `→` through all 15 slides; every entry animation replays per visit.
2. **Hover the stack** — on "One Team, Every Layer," hover any node (e.g. OptiTrack) for a what-it-is / why-it-matters tooltip.
3. **Race the pipelines** — on the Blueprint Immersive slide, hit `↻ Replay` and watch "the old way" (2–6 weeks) lose to a same-day Datasmith load.
4. **Click through a claim** — every underlined link and chip opens the portfolio page or third-party press coverage it cites (Voices of VR, BroadwayWorld, UploadVR…).
5. **Drop in real imagery** — press `M` (Move mode) and drag project stills onto the gradient placeholders (Four Seasons, Stage Presence, Christmas Carol slides), then press `A` → "Copy All" to hand the layout changes back to an AI session.

## Editing

- Deck copy lives in the `SECTIONS` array at the top of `index.html`; the interactive slides (`ix:` markers) are built by the `al-cap-layer` script at the bottom of the file.
- Theme defaults (Agile Lens brand: `#101011` bg, magenta `#FE00B5` / teal `#00C98D` accents, Manrope) are in the `D` const and `:root` vars.
- Speaker notes on every slide — `?notes` on a phone for the presenter companion view.

## Image TODOs

The Four Seasons, Stage Presence, and Christmas Carol case slides currently show branded gradient placeholders — swap in real project stills via Move-mode drag-and-drop (see Things to Try #5).

---

Built by [Agile Lens](https://www.agilelens.com) · info@agilelens.com
