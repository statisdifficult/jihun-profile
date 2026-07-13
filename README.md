# jihun-profile

Personal profile site for **Jihun Yoon** (윤지훈) — Senior Data Scientist & Researcher, CHI Lab, Asan Medical Center.

An upgraded, effects-heavy single-page profile:

- 🌌 Scatter-plot canvas (○ × △ markers) with a live least-squares regression line + animated aurora
- 📐 Graph-paper grid, drifting math symbols (∑ σ² χ² …), Greek section indices
- 🫀 ECG trace scrolling along the bottom, synaptic pulses on the constellation links
- ⌨️ Typewriter hero subtitle (per view & language)
- ✨ Scroll-reveal sections, 3D tilt cards, cursor glow, scroll progress bar
- 🔢 Animated stat counters, glowing timeline, glass accordions
- 🌗 Dark (default) / light theme toggle
- 🌐 EN / 한국어 language toggle
- 📱 Fully responsive, `prefers-reduced-motion` respected

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | Entire site (CSS + JS inlined, no build step) |
| `profile-research.png` | Research view photo |
| `profile-personal.jpg` | Personal view photo |
| `_redirects` | Netlify redirect — `/pro` serves the research-only profile |

## URL options

- `#personal` — open on the Personal view
- `?lang=ko` — start in Korean
- `?theme=light` — start in light mode
- `?pro` or `/pro` — research-only mode (Personal hidden)
