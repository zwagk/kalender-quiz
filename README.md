# Kalender - Dutch Calendar Quiz

A browser-based Dutch vocabulary game focused on the calendar. Type the Dutch translation for days of the week, months, seasons, and holidays. Four category modes, configurable timer, and a survival mode across all 35 entries.

**[▶ Play it live](https://zwagk.github.io/kalender-quiz)**

---

## How to play

1. Pick a category: **Days** (7), **Months** (12), **Seasons & holidays** (16), or **Everything** (35 - survival mode)
2. Set a time limit (No limit, 1 min, 3 min, 5 min, or custom) - no limit runs a stopwatch instead
3. Hit **Begin Quiz** - every entry appears with its emoji, type the Dutch word for each
4. Press Enter to jump to the next field
5. Hit **Check answers** when done (or wait for the timer)

---

## Modes

### List quiz (Days / Months / Seasons & holidays)
All entries in the category appear at once, each with an emoji icon. Fill in every Dutch translation, then check. Wrong answers show the correct word. Final score shows correct/total and time taken (in stopwatch mode).

### Everything (survival mode)
A random entry from all 35 items - days, months, seasons, and holidays - appears one at a time with its emoji and English name. Type the Dutch word and submit. You have **3 lives** - a wrong answer costs one. The game ends when all lives are lost. A streak counter tracks consecutive correct answers and turns red at 3+.

---

## Categories

| Category | Count | Entries |
|----------|-------|---------|
| Days | 7 | maandag, dinsdag, woensdag... zondag |
| Months | 12 | januari, februari, maart... december |
| Seasons & holidays | 16 | lente, zomer, herfst, winter, feestdag, kerstmis, kerstavond, tweede kerstdag, nieuwjaar, oudejaarsavond... |
| Everything | 35 | all of the above (survival mode) |

---

## Features

- Emoji icons as visual cues alongside each English prompt
- **4 category modes** covering all common Dutch calendar vocabulary
- **Timer modes**: countdown (1/3/5 min or custom), stopwatch, or no limit
- **Survival mode** across all 35 entries - 3 lives, streak counter, answer history
- Light and dark mode (auto-detects system preference, toggle in header)
- Fully responsive - works on mobile
- No install, no build step, no dependencies - open `index.html`

---

## Running locally

```bash
git clone https://github.com/zwagk/kalender-quiz
cd kalender-quiz
# Open index.html in any modern browser
```

No internet connection required - everything is self-contained.

---

## Tech

Single-file vanilla HTML/CSS/JS. No framework, no build step, no dependencies.

---

Made by [zwagk](https://github.com/zwagk)
