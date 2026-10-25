# Cozy Places

A pastel decorating game. Pick a place, tap things to add them, drag them around.

**Live:** https://oakleyandkat.github.io/cozy-places/

## The places

Three places of their own:

- **café** — counter, espresso machine, cake stand, bistro tables
- **campsite** — the outdoors one
- **library** — shelves, a book cart, a card catalogue

Plus **your home**, which has a house-size switcher:

| House size | Rooms you get |
|---|---|
| small | studio, kitchen, bathroom |
| medium | living room, kitchen, bedroom, bathroom |
| big | living room, kitchen, bedroom, bathroom, sunroom, playroom |

## Things to find

- **turn lights off** — every place has a night version, and lamps and candles glow
- **turn around ↻** — some furniture has a whole second side-view drawing
- **organize the fridge 🧊** — in the kitchen, a little mini-game inside the mini-game
- 175 pieces of furniture and decor in total

## What's in the folder

| File | What it does |
|---|---|
| `index.html` | The game itself |
| `manifest.json` | Tells your phone the app's name, icon and colors |
| `sw.js` | Lets the app work offline |
| `icons/` | The app icon in the sizes phones need |

Keep these together. Don't rename them.

## Install it on your phone

Open **https://oakleyandkat.github.io/cozy-places/** on your phone, then:

**iPhone / iPad (use Safari):**
1. Tap the **Share** button (square with an arrow).
2. Scroll down and tap **Add to Home Screen**.
3. Tap **Add**.

**Android (use Chrome):**
1. Tap the **⋮** menu.
2. Tap **Install app** (or **Add to Home screen**).
3. Tap **Install**.

Open it once while you're online and it works offline after that.

## Good to know

- **Your places are saved on your phone**, under the name `cozyplaces`. Each device remembers
  its own. The version you made inside Claude won't move over, so you'll start fresh.
- **Making changes later:** edit the files, then:

      git add -A && git commit -m "what changed" && git push

  GitHub Pages rebuilds in about a minute. Also open `sw.js` and change `cozy-places-v1` to
  `cozy-places-v2` (then v3, and so on) so phones pick up the new version — otherwise the old
  cached copy sticks around. Close and reopen the app to see it.

## Related

[Pocket Room](https://github.com/oakleyandkat/pocket-room) is the single-room one, with a
plum dollhouse look. Same idea, smaller and simpler, deliberately.
