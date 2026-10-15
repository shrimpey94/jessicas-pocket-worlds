# Jessica's Pocket Worlds

An original pocket-world dress-up, decorating and tile-swap puzzle game for iPhone, built as a single web page and hosted on GitHub Pages.

## Files (upload all of these to the repo)
- `index.html` — the whole game (HTML, CSS, JavaScript)
- `sw.js` — lets the game work offline after the first visit
- `manifest.json` — lets it install to the home screen like an app
- `icons/` — home-screen icons

## Install on iPhone
1. Open https://shrimpey94.github.io/jessicas-pocket-worlds/ in Safari.
2. Tap Share → Add to Home Screen.

## What's in it
- **Puzzle:** endless levels from a seeded generator (level number = seed). Each level is test-played by a bot before it's shown, and its move limit comes from how many moves the bot needed. Rhythm: 7–8 relaxing levels, then 1–2 Challenge levels.
- **Power-ups:** Ribbon (4 in a row), Glitter Bomb (L/T shape), Rainbow Charm (5 in a row), plus combos when two specials are swapped together.
- **Goals:** score, collect, glass (lvl 14+), board shapes (31+), gift boxes (80+), gold charms (150+), two goals at once (400+).
- **Dress Up:** 13 hair styles, 12 tops, 11 bottoms, 7 dresses, 11 shoes, 28 colors, 11 patterns, makeup, 5 accessory slots.
- **Decorate:** 5 compacts (one unlocks every 100 levels), 36 items, wallpapers and floors.
- **Coins:** earned from levels; unlock newer styles/decor and buy boosters in the Shop.
- **Settings (⚙️):** sound on/off, backup code to move progress to another phone.

## Build order
1. Repo and shell ✅
2. Dress-up ✅
3. Saving ✅
4. Decorate ✅
5. Puzzle core ✅
6. Power-ups ✅
7. Economy ✅
8. Level generator ✅
9. Polish (sounds, offline, backup code) ✅
10. More compacts ✅
