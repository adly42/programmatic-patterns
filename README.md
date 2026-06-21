# Programmatic Patterns

A collection of generative HTML backgrounds. Each file is fully self-contained — no build step, no dependencies. Download and open in any browser.

---

## Patterns

### [Bubble Message Background](bubble-message-background.html)

iMessage-style pill bubbles in rows across a 1920×1080 canvas. every other row flips so the tails face opposite directions. built from a real iMessage bubble SVG path. fill, outline, or liquid glass modes.

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

n-fold standing wave interference patterns rendered with Bayer ordered dithering. low frequency shows clear geometry. crank it up and it becomes film grain. based on the physics of Chladni plates.

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

### [Particle Trace](particle-trace.html)

upload any image and watch particles trace out its shape. the image becomes a brightness field, and particles flow through it using a blend of brightness-to-angle mapping (for fills) and gradient edge-following (to trace outlines). trails accumulate additively on a dark canvas. comes with a mandala flow field as the default before any image is loaded.

**Controls:**
- **Upload Image** — load any image as the particle flow field
- **Invert** — flip bright/dark so particles trace dark shapes on white backgrounds (text, logos)
- **Colors** — three color pickers for particle color assignment
- **Recolor** — reassign all particles to the current color set instantly
- **Particles** — count from 5k to 80k (default 30k)
- **Speed** — particle velocity
- **Fade** — trail persistence; slow = long glowing trails, fast = sharp short streaks
- **Clear** — reset canvas to black
- **Pause / PNG / Record** — standard export controls

---

### [Glass Flame](glass-flame.html)

double domain-warped fbm turbulence rendered with surface normals for specular highlights and iridescent edge shimmer. three modes: flame (deep red → orange → amber), glass (deep blue → aqua → ice), crystal (violet → magenta → rose-gold). the normal map drives a fresnel-based iridescent overlay and chromatic dispersion, giving the turbulence a glass-like surface quality.

**Controls:**
- **Flame / Glass / Crystal** — color palette
- **Warp** — domain warp intensity; low = gentle ripples, high = chaotic turbulence
- **Speed** — animation rate
- **Glass** — blend in iridescent shimmer and specular strength
- **Save PNG** — export current frame
- **Record** — export animated .webm video

---

### [Flow Ribbons](flow-ribbons.html)

colored ribbon waves flowing across a 16:9 canvas. webgl2 fragment shader — each ribbon gets lambertian lighting from its slope, specular highlights at the bends, and an iridescent hue shift along the x-axis. light and dark backgrounds, 3 palettes, adjustable ribbon count.

**Controls:**
- **2 – 5** — number of ribbons
- **Poly / Neon / Pastel** — color palette
- **Light / Dark** — background mode
- **Speed** — animation rate
- **Save PNG** — export current frame
- **Record** — export animated .webm video

---

More patterns coming.
