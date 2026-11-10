# Gaana EQ Studio

AI se bana gaana (Suno jaisa) chuno, dekho kahan AI jaisi kamiyan hain, phir bass aur baaki sab apni marzi se set karo.

- **AI-feel check:** 16 kHz par awaaz ka kat jana, tez 3–8 kHz, bhaari beech ki awaaz, patla bass, dabi dynamics aur stereo spread. Yeh sirf awaaz ke patterns se andaza hai, pakka saboot nahi.
- **Fix:** har problem ke liye ek button, aur "Sab auto-fix lagao".
- **Apni marzi:** Bass, Treble, Volume, Low cut aur 10-band EQ. "Original" aur "EQ ke saath" se A/B compare karo.
- **Save:** EQ wala gaana WAV file ki tarah download hota hai.

Gaana tumhare device par hi process hota hai, kahin upload nahi hota.

## Phone ya computer par install karna

1. Is repo mein Settings → Pages → "Deploy from a branch" → `main` / `(root)` → Save.
2. Thodi der baad `https://roommitara.github.io/gaana-eq-studio/` khulega.
3. Android Chrome: menu → "Install app". iPhone Safari: Share → "Add to Home Screen". Desktop Chrome: address bar mein install icon.

Install ke baad app offline bhi khulta hai.

## Files

- `index.html`: poora app (HTML, CSS aur JS ek hi file mein)
- `manifest.webmanifest`, `icon-*.png`, `icon.svg`: install ke liye
- `sw.js`: offline cache. `index.html` badlo to `sw.js` mein `CACHE` ka naam badal do.
