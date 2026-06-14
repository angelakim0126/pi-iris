# Iris's Pi Quest 🦄🌈

A kid-friendly pi-memorization game made for Iris. Sister project to her sibling's [pi-digits-game](https://github.com/angelakim0126/pi-digits-game).

Easier defaults than the sibling version: chunks of **3** digits, target **100** digits, soft wrong-handling in Practice mode (shows the right digit and keeps going instead of restarting the chunk), bigger digits, pastel rainbow theme.

## Modes

- **🌈 Practice** — Look at 3 new digits, then try to type them. Wrong digits show the answer and keep going.
- **💖 Big Try** — Type the digits of π from memory. One mistake ends the try; tracks best.
- **✨ Help Me Type** — Type the next digit. Wrong reveals the answer and continues.
- **🔍 Find Missing** — Some digits are hidden. Fill them in!

## Run locally

```bash
cd ~/Documents/pi-iris
python3 -m http.server 8000
# open http://localhost:8000
```

## Progress storage

Saved in `localStorage` under keys `iris_mastered`, `iris_best_run`, `iris_leaderboard`, `iris_test_name`, `iris_sound`.

"Start over" on the home screen clears all of these.
