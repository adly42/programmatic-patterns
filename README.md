# Programmatic Patterns

A collection of generative HTML backgrounds. Each file is fully self-contained — no build step, no dependencies. Download and open in any browser.

---

## Patterns

### [Bubble Message Background](bubble-message-background.html)

Fills a 1920×1080 canvas with iMessage-style pill bubbles of varying widths, arranged in rows. Every second row is mirrored so the tails face opposite directions. Built from a real iMessage bubble SVG path, so the tail shape and proportions are accurate.

**Controls:**
- **Regenerate** — new random layout
- **Fill / Outline** — toggle between filled bubbles and outlines only
- **Color** — pick the fill or stroke color
- **Opacity** — adjust transparency (fill defaults low for a subtle background layer)
- **Width** (outline mode) — stroke thickness
- **Save PNG / Save @2x** — export at 1920×1080 or 3840×2160

---

### [Caustics](caustics.html)

Animated caustic light patterns — the shimmering interference lines you see on a pool floor. Ported from a [146-character GLSL shader](https://x.com/XorDev/status/1827807067737985213) to a self-contained WebGL2 page. Runs at full frame rate in any modern browser with no dependencies.

**Controls:**
- **Color** — white, cyan, gold, or blue tint
- **Speed** — slow it down for a subtle ambient feel or crank it up
- **Pause** — freeze the animation

---

More patterns coming.
