# Chronicle

A 3D museum you can walk around in. I built it for fun while teaching myself about different eras of history, and it kind of grew from there.

You start in a rotunda that branches off into four wings, and every wing has its own look so you always know where you are:

- **Politics & Power** with crimson walls. Empires, revolutions, treaties, the Cold War and everything around them.
- **Science & Technology** with cobalt walls and steel trim. Big ideas, the people behind them, and the tech that came out of it.
- **Media & Literacy** with ochre plaster and brass. From the printing press to film, manga and the internet.
- **Culture & Beliefs** with ivory walls and an emerald runner. Cave paintings, religions, art, music and sport.

Walk up to any exhibit and it opens as a page you can flip through. Each one has a short hook, the main story, a few details worth knowing and a section on why it still matters today.

## Controls

| Action | Input |
| --- | --- |
| Move | WASD |
| Sprint | Shift |
| Look around | Right click and drag |
| Open an exhibit | Click it or press E |
| Walk on a phone or tablet | Hold the walk button in the corner |

## Running it

The whole thing lives in a single `index.html`, so there is nothing to install or build. Download the file (or clone the repo) and open it in a browser. You will want an internet connection since the fonts load from Google Fonts.

```bash
git clone https://github.com/mominmansoor/chronicle-museum
cd chronicle-museum
# then just open index.html
```

## How it's made

It runs on Three.js. The rooms, walls and lighting are all built in code, and the exhibit text sits in plain data entries in the same file.
