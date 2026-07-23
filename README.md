# Run The Votes

A South African political satire side-scrolling runner game. Pick a politician, choose your dirty trick, and run for your political life — dodging potholes, minibus taxis, and load shedding while collecting votes.

**Live:** [hermanboock.github.io/RSA-Vote-Runner](https://hermanboock.github.io/RSA-Vote-Runner)

---

## How to Play

1. **Select your candidate** — choose from four SA political archetypes, each with unique stats across Charisma, Promises, and Scandals
2. **Choose your dirty trick** — pick a power that suits your play style
3. **Run** — collect vote envelopes, dodge obstacles, survive as long as possible
4. **Score** — your Campaign Score combines votes collected (×10) and distance travelled

### Controls

| Platform | Jump | Double Jump |
|----------|------|-------------|
| Desktop | Space / ↑ | Press twice |
| Mobile | Tap JUMP button | Tap twice |

---

## Characters

| Character | Party | Tagline |
|-----------|-------|---------|
| Chief ANC | African National Congress | Power to the People |
| Captain VF | Vryheidsfront Plus | Restore and Rebuild |
| Comrade EFF | Economic Freedom Fighters | Son of the Soil |
| Leader DA | Democratic Alliance | Let's Get RSA Working |

Each character has balanced stats averaging 69 across Charisma, Promises, and Scandals — no character is strictly better than another.

---

## Powers (Dirty Tricks)

| Power | Effect |
|-------|--------|
| 🗳️ Buy Votes | Vote envelopes are magnetically pulled toward you |
| ⚡ Eskom Bribe | Generator obstacles no longer trigger darkness |
| 💰 Tenderpreneurship | Every vote counts as two on the scoreboard |
| 🏛️ State Capture | Run through one obstacle without consequence |
| 🕺 Zuma Dance | Double jump with significantly extra height |

---

## Obstacles

- **Pothole** — dodge or jump. Flashes an orange warning light during load shedding.
- **Minibus Taxi** — the classic SA HiAce. During load shedding its headlight illuminates the terrain ahead.
- **Generator (Load Shedding)** — hitting one plunges the screen into darkness. Only a small torch circle around your character and the taxi headlight remain visible.

---

## Scoring

```
Campaign Score = (Votes Collected × 10) + Distance (metres)
```

Your personal best is stored locally in the browser.

---

## Sentiment Research

Run The Votes is designed as more than a game. Anonymous character and power selection data, when aggregated over time, serves as a proxy for political sentiment:

- **Character choice** reflects cultural resonance — who people find entertaining or relatable, which may differ significantly from actual voting intent
- **Power choice** reflects political worldview — cynicism, distrust of institutions, or alignment with particular narratives
- **The combination** of character + power reveals nuanced perceptions that direct polling cannot easily capture

Post-2026 election, aggregated gameplay data can be compared against actual results to measure the gap between cultural affinity and electoral trust.

---

## Tech Stack

- Single HTML file — no build step, no dependencies
- Vanilla JS + Canvas API for all game rendering
- Teko Bold (Google Fonts) as the game font
- Official vertical SA flag SVG as background
- Deployed via GitHub Pages

---

## Development

All game logic, assets, and UI live in `index.html`. To run locally just open the file in a browser — no server required.

To deploy: push `index.html` to the `main` branch of the GitHub repository. GitHub Pages auto-deploys within ~60 seconds.

---

## Credits

Built by [Herman Boock](https://hermanboock.github.io) as a satirical commentary on South African politics ahead of the 2026 elections.

*Not affiliated with any political party. All characters are fictional satirical archetypes.*
