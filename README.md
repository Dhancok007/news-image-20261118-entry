# THE WORLD IN ONE PICTURE — Wednesday 18 November 2026

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/Dhancok007/news-image-20261118-entry/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/Dhancok007/news-image-20261118-entry/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One image that sums up the world's news of **Wednesday 18 November 2026**:

- **America sinks five Iranian tankers** — the US says it sank five Iranian oil tankers in the Gulf of Oman; Iran answers with attacks on ten ships near Hormuz, missiles at a US base in Jordan, and drones over Bahrain and Kuwait.
- **Kerch Bridge hit again, Washington scolds Kyiv** — Ukraine strikes the Crimean bridge a second night running on the eve of the Trump–Xi–Putin summit.
- **Netanyahu bypassed** — President Herzog asks Gadi Eisenkot to form Israel's next government.
- **Gaza: cold closes in** — the UN warns the displaced will die of cold as the ceasefire nears collapse.
- **COP31 goes down to the wire** — 144 disputed items in the draft climate deal at Antalya.
- Also today: North Korea fires a ballistic missile, Robert Pattinson is the new James Bond, a Pakistani plotter is jailed 27 years in the US, and Democrat Peltola flips Alaska's Senate seat.

## How it is built

`poster.html` is the poster (headlines, decks and two hand-drawn SVG scenes: a Gulf of Oman war-at-sea map and the Kerch Bridge at night). It was rendered once to `entry.png` (1024×1024 PNG) with a headless browser. `main.ts` (Node 22, standard library only) checks the image against the competition's limits and copies it to `/output/entry.png`, byte for byte, on every run.

Run it locally:

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
