# Cheat Vault — GTA San Andreas & GTA V

Fast, single-file cheat reference for **GTA San Andreas** and **GTA V Story Mode**. PlayStation, Xbox, PC and in-game phone codes.

**[▶ Live Demo](https://zengm5057-sudo.github.io/sa-cheats)**

---

## Features

- Two tabs: **GTA San Andreas** (78 cheats) and **GTA V Story Mode** (36 cheats)
- Platform switcher: PlayStation ↔ Xbox. GTA V adds **PC** (typed words) and **Phone** (1-999 numbers)
- **Version switch (GTA V):** PS4 · PS5 · Xbox One · Series vs PS3 · Xbox 360. Hides cheats the old-gen versions can't run
- Version-differences table, plus per-card tags: *New-gen only*, *Unlock first*
- Real-time search by name, button, cheat word or phone number
- Category filters per game, live counts
- Favorites (localStorage, kept per game) with clipboard export
- Grid / List view · Sort A→Z · Random cheat
- Dark / Light theme · One-click copy · Toast notifications
- Deep links: `#sa` and `#gta5`
- Keyboard shortcuts: `/` focus search · `Esc` clear
- Zero dependencies — pure HTML + CSS + JS

---

## GTA V: what works where

| Feature | PS3 · 360 | PS4 · One | PS5 · Series | PC |
|---|:-:|:-:|:-:|:-:|
| Button combos | ✓ | ✓ | ✓ | – |
| Typed console words | – | – | – | ✓ |
| Phone numbers (1-999-…) | – | ✓ | ✓ | ✓ |
| Dodo · Duke O'Death · Kraken | – | ✓ | ✓ | ✓ |
| Director Mode · Black phone | – | ✓ | ✓ | ✓ |

- **PS4 and PS5 share every code.** No PS5-only cheat found in any source checked.
- **Dodo, Duke O'Death, Kraken** are phone/PC only and locked until unlocked in the save:
  - Dodo → finish the *Sea Plane* random event
  - Duke O'Death → finish the *Duel* random event (a few guides say Tonya's first mission instead)
  - Kraken → photograph all 20 animals (*Wildlife Photography Challenge*)
- **Black Cell Phone:** only confirmed effect is a black phone. Some guides claim random explosions; unverified.
- **No money cheat exists.** Cheats are story mode only and disable trophies/achievements until you reload a clean save.

### Phone cheats

Press Up for the phone → Contacts → Square (PS) / X (Xbox) for the dial pad → dial → call.
Phone numbers are generated from the cheat word using phone keypad letters (e.g. `TURTLE` → `1-999-887853`).

---

## Sources

Cross-checked against GTA BOOM, GamesRadar, PC Gamer, GamesRead and Twinfinite. One typo found and fixed: GTA BOOM lists `LIQUOR` as `547-861`; the keypad gives `547867` (matches other sources).

---

## Deploy to GitHub Pages

```bash
git add index.html README.md
git commit -m "feat: rename to Cheat Vault, add GTA V story mode tab"
git push
```

First time:

```bash
git init
git remote add origin https://github.com/zengm5057-sudo/sa-cheats.git
git add index.html README.md
git commit -m "feat: initial release"
git branch -M main
git push -u origin main
```

Then **Settings → Pages → Deploy from branch → main / root → Save**.

Live at: `https://zengm5057-sudo.github.io/sa-cheats`

> The repo is still named `sa-cheats`. Renaming it (e.g. `cheat-vault`) works — GitHub redirects the old URL. Update the links in `index.html` and this file if you do.

---

## Contributing

1. Fork the repo
2. Edit `SA_CHEATS` (San Andreas) or `V_RAW` (GTA V) in `index.html`
   - GTA V rows: `[name, category, PC word, PS combo or null, note, options]`
   - Phone number is generated from the PC word. Use `null` for phone/PC-only cheats
3. Open a Pull Request

---

MIT License · Built by [Ahmed Rade](https://github.com/zengm5057-sudo)
