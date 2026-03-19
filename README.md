# 🎮 Pico Dot Battler

> Draw your pixel art character and battle!  
> ドット絵を描いて、育てて、戦わせるブラウザゲーム

![version](https://img.shields.io/badge/version-0.1.0-blue)
![platform](https://img.shields.io/badge/platform-mobile%20browser-green)
![file](https://img.shields.io/badge/files-single%20HTML-orange)

---

## 📱 Play

Open `index.html` in a mobile browser — no server required.

> スマートフォンのブラウザで `index.html` を開くだけでプレイできます。

---

## 🕹 How to Play

1. **Draw** — Paint your character on the 16×16 pixel grid
2. **Raise** — Stats are auto-calculated from your color choices
3. **Battle** — Watch your character fight automatically, tap skills to intervene

| Color | Stat |
|---|---|
| 🔴 Red / Orange | ATK |
| 🔵 Blue / Cyan / Black | DEF |
| 🟢 Green | HP |
| 🟣 Purple / Pink | SPD |
| 🟡 Yellow / White | SP Recovery |

---

## ✨ Features

- 🎨 **Pixel Art Editor** — 16×16 grid, touch drawing, 10-step undo, fill tool
- ⚔️ **Auto Battle** — Fully automatic with skill interrupts
- 🗺️ **5 Stages** — Field / Cave / Castle / Beach / Volcano (random each battle)
- 📈 **Character Growth** — Level up to 50, skill tree, equipment, evolution at Lv20
- 🛒 **Shop** — Unlock new colors, buy equipment, purchase evolution stones
- 🏆 **Ranking** — Top 10 leaderboard with pixel art display
- 🔊 **Sound Effects** — Web Audio API (no external files)

---

## 📂 Files

```
index.html       ← Game (single file, all-in-one)
game-design.md   ← Full game design document
todo.md          ← Development task list
manifest.json    ← PWA placeholder (future)
```

---

## 🔧 Tech Stack

- HTML / CSS / JavaScript — vanilla, no frameworks
- Canvas 2D API — battle animation & pixel art rendering
- Web Audio API — sound effects
- localStorage — save data persistence

---

## 🗺️ Roadmap

| Version | Features |
|---|---|
| v0.1.0 | Core gameplay, editor, battle, shop, ranking ✅ |
| v0.2.0 | Equipment enhancement, evolution system, stage drops |
| v0.3.0 | BGM, PWA support, character export/import |

---

## 📄 License

Personal project — all rights reserved.
