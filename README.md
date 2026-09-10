# Family Zoo — v10 — Switchable Devices

A radio bolted to a shelf in the supply room can be switched on and off to play music. Shows SwitchableTrait on its own — no light source involved — and contrasts it with OpenableTrait.

Step 10 of the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial — a progressive walkthrough of the [Sharpee](https://sharpee.net) TypeScript interactive fiction engine, from a single room to a full multi-file story.

## What this step teaches

- Standalone SwitchableTrait for non-light devices
- switch on/off and turn on/off verb aliases from stdlib
- Semantic distinction between switch (devices) and open (barriers)
- Combining SwitchableTrait with SceneryTrait for fixed appliances
- Patterns for future device combinations

## Playing

Open `play.html`, or preview the folder:

```bash
python -m http.server 8000 --directory familyzoo-v10
```

## Building

This is a **frozen 0.9.x TypeScript version**. The built player in this folder is the published artifact; it is re-laid from `browser/` by the workspace build:

```bash
python ../tools/build.py familyzoo-v10
python C:/code/ifhub/tools/ship.py familyzoo-v10
```

The authoring tree for every version lives in the [familyzoo](https://github.com/Johnesco/familyzoo) repo.
