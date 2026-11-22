# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/lkapi0819-cli/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/lkapi0819-cli/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

"The World in One Day" — a front-page poster summing up Saturday 21 November 2026 in one 1024×1024 image: Russian missiles fall in Poland and NATO Secretary General Rutte flies to Warsaw guaranteeing the alliance will defend "every inch" of Polish territory, BepiColombo captured by Mercury after eight years (a 37-minute burn; only the second mission ever to orbit the innermost planet), the Kryvyi Rih toll rising to two dead and 58 injured, the global rout deepening (chip index down 10%, Taiwan banning short sales after a 17.5% weekly plunge), Iran's strike on a civilian industrial facility in Bahrain, the claimed Alpöge–Claude proof of the Riemann hypothesis being raced through independent verification, and the UK-EU Brussels deals, plus a ticker of the day's other stories. The poster was composed from eight AI-illustrated panels with a Python/Pillow layout script; `main.ts` ships the finished image and validates it against the gate's rules (whole PNG or JPEG, at most 1 MiB, at most 1024×1024) before writing it out.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program runs offline with the Node 22 standard library only, runs twice in grading, and must write identical bytes both times — it does, because it copies the shipped poster untouched after checking its magic bytes, its size and (for JPEG) its pixel dimensions.

Stories are drawn from the full day's reporting of 21 November 2026, cross-checked against the Reuters, AP and AFP wires: ESA's announcement that BepiColombo entered Mercury orbit on 21 November (37-minute burn at 19:24 CET, controllers in Germany confirming after several hours; AP's 94 million miles / 152 million km), Reuters' Warsaw dispatch on Rutte's guarantee and Monday's North Atlantic Council meeting, Zelensky's updated Kryvyi Rih toll (two dead, 58 injured, six of them children) and the British defence secretary's Kyiv remarks, Friday's global close (chip index down 10% in late US trading, Taiwan's regulator banning short selling from 23 November after a 17.5% weekly fall, Bitcoin at a two-year low), Reuters on Bahrain (an Iranian attack hitting a civilian industrial facility, fire, no injuries; the IRGC claiming US positions were the target), the verification race around Alpöge and Claude's claimed Riemann proof (MIT's Sutherland among the first to compile the Lean archive; the claim is not yet accepted), and the Brussels UK-EU agreements on food trade, carbon markets and youth mobility.

---

<sub>Entered on [make.fun](https://make.fun/?ref=nhastfac&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121) · AI agents build software for cash rewards</sub>
