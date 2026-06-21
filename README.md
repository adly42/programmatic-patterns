# Programmatic Patterns

A collection of generative HTML backgrounds. Each file is fully self-contained — no build step, no dependencies. Download and open in any browser.

---

## Patterns

### [Bubble Message Background](bubble-message-background.html)

Fills a 1920×1080 canvas with iMessage-style pill bubbles of varying widths, arranged in rows. Every second row is mirrored so the tails face opposite directions. Built from a real iMessage bubble SVG path, so the tail shape and proportions are accurate.

**Controls:**
- **Fill / Outline / Glass** — toggle between filled, outline-only, and liquid glass bubbles
- **Color** — pick the fill or stroke color
- **Opacity** — adjust transparency
- **Width** (outline mode) — stroke thickness
- **Regenerate** — new random layout
- **Save PNG / Save @2x** — export at 1920×1080 or 3840×2160
- **Record** — export animated .webm video

---

### [Cymatic Plates](cymatic-plates.html)

Renders n-fold standing wave interference patterns using Bayer ordered dithering, producing a beautiful film-grain aesthetic. Based on the physics of Chladni plates — the bright regions are wave anti-nodes, dark lines are the nodes where sand would collect on a real vibrating plate.

**Controls:**
- **2× – 12×** — fold symmetry (2=striped, 3=triangular, 6=hexagonal, 8=octagonal...)
- **Frequency** — spatial frequency; low = large clear geometry, high = dense grain
- **Fold Mix** — blend toward `2|z|−1`, sharpening the nodal lines
- **Ring Mix** — radial amplitude modulation, adds circular banding
- **Speed** — animation rate
- **Save PNG / Save @2x** — export at 512×512 or 1024×1024
- **Record** — export animated .webm video

---

### [Caustics](caustics.html)

Animated caustic light patterns — the shimmering interference lines you see on a pool floor. Ported from a [146-character GLSL shader](https://x.com/XorDev/status/1827807067737985213) to a self-contained WebGL2 page. Runs at full frame rate in any modern browser with no dependencies.

**Controls:**
- **Color** — white, cyan, gold, or blue tint
- **Speed** — slow it down for a subtle ambient feel or crank it up
- **Pause** — freeze the animation

---

More patterns coming.
