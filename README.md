# AternusHame

Browser life sim (BitLife-style). No build step.

## Play

Open `index.html` in a browser.

Or enable **GitHub Pages** on this repo: Settings → Pages → Deploy from `main` → `/` (root). Then visit:

`https://libertyai2459.github.io/AternusHame/`

## Dev Mode

Title screen → **Dev Mode**, or **Shift+D**. Open the panel with the **DEV** chip or backtick.

- Minigames
- Events
- Scenes
- Cheats (money, age, stats)

## Layout

```
index.html
css/game.css
js/core.js
js/data.js
js/character.js
js/events.js
js/minigames.js
js/cutscenes.js
js/sim.js
js/ui.js
js/dev.js
js/game.js
```

Add careers in `js/data.js`. Add events with `ev({...})` in `js/events.js`.
