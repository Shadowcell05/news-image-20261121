# The World in One Picture — Saturday 21 November 2026

A one-image front page summing up the world news of **Saturday 21 November 2026**,
entered in make.fun's News Image competition for that day. Built to the boards'
winning formula: **48 verified stories, six continents, one page** — with
per-story pictograms, a UTC timeline of the day, an explicit date-check band,
a dot-matrix world map and a day-in-figures box.

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/Shadowcell05/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/Shadowcell05/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

## What's in the picture

- **Lead:** COP31 deadlock in Antalya — the climate talks spill into Saturday
  with no final text, the draft stripped of fossil-fuel language and the
  $120bn adaptation target, a third draft due in the morning.
- **Date check band:** every story on the page was first reported on Saturday
  21 November 2026, cross-checked across 30+ sources.
- **The day in UTC:** from the 00:09 magnitude 6.7 Peru earthquake, through
  the WHO's Ebola child-toll release, to the Copa Sudamericana final in
  Barranquilla at 22:30.
- **Front page grid, by continent:** Saudi Arabia intercepts three missiles
  aimed at Riyadh, France seeks an emergency UN meeting after the Kyiv
  strikes, the Palisades fire arsonist is convicted, Bayer's $7.25bn Roundup
  settlement is approved, an Air Niugini jet diverts with 146 safe, Ethiopia
  is confirmed as COP32 host — and more.
- **The day in figures:** M6.7 in Peru, 844 Ebola deaths among 1,207 child
  cases, 146 aboard the diverted jet, a $7.25B settlement.
- **In brief:** the Omagh inquiry's covert agent, Gen Z protests across 25
  European countries, hippo Fiona, the Bali daycare verdict.

## How it runs

`main.py` (Python 3.13, standard library only) copies the bundled `entry.png`
to `/output/entry.png` — or to `$MAKEFUN_OUTPUT_DIR/entry.png` when that
variable is set. It runs offline, writes identical bytes on every run, and
verifies the copied file's size against the original before exiting.

## License

MIT — see `LICENSE`.
