# UK Fuel & Journey Cost Calculator

Journey cost calculator for petrol, diesel and EVs. UK imperial MPG, km/L and L/100km, EV tariffs,
GBP/EUR, tolls and ULEZ/CAZ, cost per person, vehicle comparison, unit converter and saved trips.

Static site, no build step. Works offline and installs as an app (Chrome on Android: menu, then
**Add to Home screen** / **Install app**).

## Live data
- **Exchange rate:** ECB reference rate from [Frankfurter](https://frankfurter.dev), no key needed.
  Refreshed automatically every 6 hours, or tap the rate button.
- **Live fuel prices (optional):** Gemini with Google Search grounding. Add your own key under
  Settings (gear icon). Get one at [Google AI Studio](https://aistudio.google.com/apikey).
  The key is stored only in your browser's localStorage and only sent to Google.

## Hosting
GitHub Pages: Settings, Pages, deploy from branch `main`, folder `/ (root)`.

When you change files, bump `VERSION` in `sw.js` so installed copies pick up the update.
