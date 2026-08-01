# Emporium Citadel 
# Emporium Command — Genesis

Emporium Command: Genesis is a single-file, browser-based sci-fi command dashboard built entirely in HTML, CSS, and vanilla JavaScript. No frameworks. No dependencies. No build step. Just open the file and step into the role of the Founder.

## What Is This?

A dark, cinematic dashboard that simulates a 10-zone network topology under threat from entropy. You play as the Founder — the sole entity capable of stabilising the grid. The interface features:

- A full intro cinematic with timed narrative, particle effects, and starfield generation
- An interactive topology map with SVG conduits, nebulae, and a glowing Founder avatar
- Real-time zone instability tracking across 10 distinct sectors
- A live PICT-ITD diagnostic engine — a tiny neural network running in your browser that simulates vibration signals and classifies zone states
- JARVIS Directive mission controls with accept / escalate / dismiss actions

## Features

| Feature | Description |
|---|---|
| Intro Cinematic | 13-line narrative sequence with blur-to-focus text reveals, entropy particles, and a starfield birth |
| Topology Map | Interactive SVG map with animated conduits, nebulae, vortex rings, and zone nodes |
| 10 Live Zones | Each zone has unique lore, instability %, condition state, and SVG iconography |
| PICT-ITD Diagnostic | A 3→16→4 feed-forward neural network that simulates vibration signals and outputs polarity, coherence, and classification |
| Real-Time Scanning | Auto-scan tick every 10s randomises zone instability; diagnostic updates every 5s |
| Founder Avatar | A pulsing, ping-animated entity that moves to whichever zone you select |
| Mission Controls | Accept, Escalate, or Dismiss missions per zone with live logging |
| Responsive Status | Network coherence banner shifts between Critical (red), Warning (orange), and Stable (teal) |
| Zero Dependencies | Pure HTML/CSS/JS. Works offline. Drop it in a browser and go. |

## The 10 Zones

| Zone | Tag | Condition | Core Threat |
|---|---|---|---|
| The Hub | Signal bridge | Unstable | Signal noise, logic drift |
| University | Curriculum sync | Stable | Curriculum fragmentation |
| Vortex Lab | Spatial logic | Critical | Rotational instability |
| Photonic Conduit Lab | Quantum interface | Stable | Light-path scattering |
| Mustard Seed Lab | Morphogenics | Inverting | Qubit collapse |
| Cyber Tower | Data lattice | Unstable | Retention glitches |
| Healing Arts Institute | Resonance field | Stable | Resonance dissonance |
| Cultural Nexus | Domain sync | Stable | Domain desynchronisation |
| Knight Citadel | Field discipline | Unstable | Field-discipline breakdown |
| Angel Spire | Photonic core | Critical | Photonic dimming |

## How to Run

1. Download or clone the repository
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
3. Watch the intro, or click Skip Intro
4. Click any zone on the map or sidebar to deploy the Founder
5. Use Accept Mission to lower instability, or Escalate to raise it

No server required. No npm install. No bundler. It just works.

## The PICT-ITD Diagnostic Engine

Beneath the UI lies a functioning (if tiny) neural network:

- **Input layer:** 3 features — polarity, coherence, vector magnitude
- **Hidden layer:** 16 neurons with tanh activation
- **Output layer:** 4 classes — stable, unstable, critical, inverting
- **Signal simulation:** Per-zone condition generates a synthetic vibration signal with harmonic distortion and Gaussian noise
- **Spectral analysis:** A custom DFT computes power entropy to derive the coherence score

All of this runs client-side in real time, producing live confidence percentages for the active zone.

## Philosophy

This project is part interface design exercise, part narrative experiment. It treats personal organisation — study, health, security, creative work — as a galactic command structure. The zones map to real-life domains:

- **University** = learning and focus
- **Cyber Tower** = codebase and digital hygiene
- **Healing Arts Institute** = sleep, nutrition, movement
- **Knight Citadel** = passwords, backups, discipline
- **Angel Spire** = research energy and creative drive

The dashboard asks: what if managing your life felt like commanding a space-faring civilisation?

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, keyframe animations, backdrop-filter
- **JavaScript** — DOM manipulation, setTimeout cinematic sequencing, procedural generation, neural network inference
- **SVG** — inline icons and animated conduit lines
- No external assets — everything is self-contained (except the optional squadren_anime.png intro image)

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+


Requires support for CSS custom properties, CSS Grid, and backdrop-filter.

---

*"The only one standing in the way is you."*
