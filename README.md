# War Wrapped - AI project

**Spotify Wrapped, but for rocket sirens.** Drop your Google Timeline export onto a single HTML file and get a personal, swipeable recap of every siren that caught you — where you were, how long you spent in shelters, which nights it woke you, which sirens you dodged by being abroad — ending with a printable "Civilian Under Fire" ID card with your name on it.

One file. No install. No server. **No internet.** Nothing you drop ever leaves your device.

## How to use

1. On your phone for Android - Settings - Location - Location Services - Google Timeline - export date - Timeline.json
2. Open `war-wrapped.html` in any modern browser (works from a USB stick on airplane mode).
3. Drop the file in, pick your war — Lions Roar, the 12-Day War, Drones Night, or everything since Oct 7 — and tap to begin.

## Credits

**Made entirely by AI.** JS is a languge I dont feel comfortable enough in to code this project so I used the new anthropics Fables5 for most of it
**Made by a human:**
- The idea, and every feature call: Every single stat was thought and human written, along with its UX UI.
- The taste — The UI was very important to me, reference photos and scrict guidance.
- The Data - Finding the Data to pull was one of the hardest challenges, I ended up Using Tzeva Adoms public endpoints for the Sirens data, location data and polygons.

## Data sources

[tzevaadom.co.il](https://www.tzevaadom.co.il) historical archive · area polygons & metadata from the open-source `amitfin/oref_alert` project · Google Fonts (Heebo, Suez One — OFL) · Leaflet 1.9.4 ·

*Please, May this file never need an update.* I dont wanna download Tzeva Adoms database again.
