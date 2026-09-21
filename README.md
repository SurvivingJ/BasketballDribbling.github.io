# BasketballDribbling.github.io 🏀

A single-file basketball dribbling trainer. Set a tempo, pick your drills, and go —
it runs an **audible metronome** to dribble to and **calls out each drill by name** so
you never have to look at the screen while the ball's in your hand.

**[Open the app »](https://basketballdribbling.github.io)**

## Features

- **Audio metronome** — a click track built on the Web Audio API keeps you locked to
  the beat, with an accented downbeat on the "1".
- **Spoken drill callouts** — the app announces each move out loud (SpeechSynthesis),
  so your eyes stay on the court, not the phone.
- **Three workout styles**
  - *Random* — moves fired at you in random order.
  - *Sequence* — cycle through your selected drills in order.
  - *Pyramid* — drill length ramps up then back down to build endurance.
- **Pick your drills** — enable/disable any move, or add your own custom drills.
- **Tap tempo & BPM presets** for dialling in the right speed.
- **Live progress** — pulsing basketball beat indicator, per-drill ring, overall
  timer, and a "next up" preview.
- **Pause / resume / stop** (keyboard: <kbd>Space</kbd> to pause, <kbd>Esc</kbd> to stop).
- **Screen wake-lock** so your phone won't sleep mid-set.
- **Post-workout summary** with time trained, drills completed, and dribbles hit.
- **Settings are saved** locally between sessions.

## Requirements

None. It's one `index.html` file with **no external dependencies**, no build step,
no accounts, and no tracking — it works fully offline.

---
Originally built quickly with the help of GPT as an experiment; rebuilt and expanded
since.
