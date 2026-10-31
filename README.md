# Learny

A Pokémon-style learning adventure for any topic, packaged as an iPhone Home Screen app.

- `index.html` is built by `build.py` from `source-learny.html` (the same game that runs as a Claude artifact). Don't edit it by hand.
- Outside Claude, lessons and questions come from Google's free Gemini API. Each player adds their own key in Settings; it stays on their device.
- `sw.js` keeps the app working offline between AI calls. It is rebuilt with a new version on every build so phones pick up updates.

Rebuild after changing the game:

    python3 build.py
