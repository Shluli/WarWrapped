# 🚨 War Wrapped - AI project

**Spotify Wrapped, but for rocket sirens.** Drop your Google Timeline export onto a single HTML file and get a personal, swipeable recap of every siren that caught you — where you were, how long you spent in shelters, which nights it woke you, which sirens you dodged by being abroad — ending with a printable "Civilian Under Fire" ID card with your name on it.

One file. No install. No server. **No internet.** Nothing you drop ever leaves your device.

## How to use

1. On your phone for Android - Settings - Location - Location Services - Google Timeline - export date - Timeline.json
2. Open `war-wrapped.html` in any modern browser (works from a USB stick on airplane mode).
3. Drop the file in, pick your war — Lions Roar, the 12-Day War, Drones Night, or everything since Oct 7 — and tap to begin.

## What's inside the 2 MB

- **The complete siren archive, embedded.** Every tzevaadom alert Oct 2023 → Mar 2026, plus the Mar–Jul 2026 gap reconstructed from official Pikud HaOref history (validated 65/65 minute-agreement on overlap data), gzipped into the file itself. That's why CORS, proxies, and Wi-Fi are all irrelevant.
- **City polygons + coordinates** for 1,449 areas, so "were you inside the alert zone" is answered with real geometry, not guesses.
- **Travel detection** that finds your trips abroad (and ignores the GPS jamming that teleports every Israeli phone to Beirut airport), then tells you *when these hit home, you were somewhere around 🇬🇷…*
- **Leaflet, inlined**, for the siren map. **Heebo + Suez One**, subsetted and embedded, so Hebrew looks right offline.
- **A canvas PNG exporter** that renders your stat card at full resolution for sharing.
- Handles both classic `Records.json` and the modern on-device `Timeline.json` export — including a memory-light fast scanner so 67 MB files open fine on phones, and a JSON-recovery parser for truncated exports.

## Credits

**Made entirely by AI.** JS is a languge I dont feel comfortable enough in to code this project so I used the new anthropics Fables5 for most of it
**Made by a human:**
- The idea, and every feature call: Every single stat was thought and human written, along with its UX UI.
- The taste — The UI was very important to me, reference photos and scrict guidance.
- The Data - Finding the Data to pull was one of the hardest challenges, I ended up Using Tzeva Adoms public endpoints for the Sirens data, location data and polygons.

## Data sources

[tzevaadom.co.il](https://www.tzevaadom.co.il) historical archive · area polygons & metadata from the open-source `amitfin/oref_alert` project · Google Fonts (Heebo, Suez One — OFL) · Leaflet 1.9.4 ·

*Stay safe. May this file never need an update.*
