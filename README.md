# Family Zoo — v10: Switchable Devices

A radio in the supply room, a feed dispenser in the petting zoo, a penny press in the gift shop — and the shop itself, whose description is stitched from a cycling phrase.

Step 10 of sixteen in the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial for [Chord](https://sharpee.net/chord/), the authoring language of the [Sharpee](https://sharpee.net) interactive fiction engine.

## What this step adds

- `switchable` and TURN ON / TURN OFF
- `on` clauses that fire when a device is used
- `define phrase pins, cycling` — a different line each time
- `{pins}` — binding a phrase into a description

## The source

The whole step is one file: [`familyzoo-v10.story`](./familyzoo-v10.story) — the step before it plus the ideas above. The chapter that walks through it is [`docs/v10-switchable-devices.md`](./docs/v10-switchable-devices.md).

## Playing and testing

```bash
npx sharpee play
npx sharpee test          # replays familyzoo-v10.tests.json
python ../tools/build.py familyzoo-v10 --force
```

## Engine

Pinned to `@sharpee/*` **5.3.0** (Chord 3.6.0), held there by an `overrides` block: 5.3.1 publishes broken subpath exports and breaks `sharpee test`.

The 0.9.x TypeScript edition this replaced is kept in [`legacy/`](./legacy).
