<div align="center">

# 🐰 BunBun’s Carrot Run 🥕

**A tiny pixel-art platformer that lives in a single HTML file.**
Collect carrots, bop foxes, and glide over pits with the tote bag.

[![Open source](https://img.shields.io/badge/open_source-MIT-ffb84d?style=for-the-badge)](LICENSE)

![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-e34f26?logo=html5&logoColor=white)
![Vanilla JS](https://img.shields.io/badge/vanilla-JavaScript-f7df1e?logo=javascript&logoColor=black)
![Web Audio](https://img.shields.io/badge/Web_Audio-chiptune-7db6ff)
![Zero assets](https://img.shields.io/badge/assets-zero-2ec27e)
![Mobile friendly](https://img.shields.io/badge/mobile-touch_controls-ff7aa2)
![License: MIT](https://img.shields.io/badge/license-MIT-blue)

<img src="docs/hills.png" alt="BunBun jumping off a moving platform in Burrow Hills" width="820" />

</div>

## ✨ Features

- **3 hand-built stages**: Sunny Meadow, Burrow Hills and Carrot Summit, with checkpoints along the way
- **Feels good to play**: coyote time, jump buffering, variable jump height and squash & stretch
- **Tote bag power-up**: hold jump to glide, and it absorbs one hit
- **Foxes** patrol the levels. Bop them from above and avoid them everywhere else
- **Moving platforms, spikes and pits** to keep you on your toes
- **Synthesized chiptune + SFX** made live with the Web Audio API
- **Everything is drawn in code.** There are no image or sound files
- **Keyboard and touch controls**, pause, mute, and a saved best time

<table>
  <tr>
    <td><img src="docs/title.png" alt="Title screen" /></td>
    <td><img src="docs/summit.png" alt="Gliding with the tote bag on Carrot Summit" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Title screen</sub></td>
    <td align="center"><sub>Gliding with the tote bag on Carrot Summit</sub></td>
  </tr>
</table>

## 🎮 Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | <kbd>A</kbd> <kbd>D</kbd> or <kbd>←</kbd> <kbd>→</kbd> | ◀ ▶ |
| Jump | <kbd>Space</kbd> / <kbd>W</kbd> / <kbd>↑</kbd> | ▲ |
| Glide (with tote) | hold jump while falling | hold ▲ |
| Pause | <kbd>P</kbd> / <kbd>Esc</kbd> | ❚❚ |
| Mute | <kbd>M</kbd> | — |

## 🚀 Play it

The game isn't hosted anywhere right now (see [History](#-history)), but it runs entirely in your browser. There's nothing to build or install. Clone the repo and open the file:

```bash
git clone https://github.com/Mattlo0546/bun-buns-carrot-run.git
open bun-buns-carrot-run/index.html
```

Tip: add `?stage=2` or `?stage=3` to the URL to jump straight to a stage.

## 🛠️ Make your own levels

Levels are ASCII maps near the top of the script in [`index.html`](index.html). Edit the characters and refresh:

```
#  ground          B  stone block     ^  spikes
S  start           C  carrot          T  tote bag
F  fox             K  checkpoint      M  moving platform
G  goal
```

Physics, speeds and timings are all in the `CONFIG` object at the top of the script.

## 📜 History

BunBun’s Carrot Run started life as a small side project. It was later hosted on Vercel as part of **opengame** (opengame.me), a home for little browser games.

That hosting has since been retired. The game is now fully open source here, in one self-contained `index.html` you can play offline, fork and remix.

## 🤝 Contributing

Contributions are welcome! New levels, sprites, sounds and bug fixes are all fair game.

1. Fork the repo and create a branch
2. Make your changes in `index.html` (no build step needed)
3. Open it in a browser to test, then open a pull request

Found a bug or have an idea? [Open an issue](https://github.com/Mattlo0546/bun-buns-carrot-run/issues).

## 📄 License

Released under the [MIT License](LICENSE). You're free to use, modify and share it.
