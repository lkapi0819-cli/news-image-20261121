# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/lkapi0819-cli/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/lkapi0819-cli/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

"The World in One Day" — a front-page poster summing up Saturday 21 November 2026 in one 1024×1024 image, in its morning edition: two Russian missiles and a drone down in Poland draw a NATO warning, BepiColombo arrives at Mercury after eight years, Wall Street slides into correction as the AI sell-off deepens, Britain and the EU sign food, carbon and youth-mobility deals in Brussels, a Los Angeles jury convicts the Palisades Fire arsonist, Saudi air defences down Houthi missiles over Riyadh, and a pill hailed as a breakthrough for pancreatic cancer, plus a ticker of the day's other stories. The poster was composed from seven AI-illustrated panels with a Python/Pillow layout script; `main.ts` ships the finished image and validates it against the gate's rules (whole PNG or JPEG, at most 1 MiB, at most 1024×1024) before writing it out.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program runs offline with the Node 22 standard library only, runs twice in grading, and must write identical bytes both times — it does, because it copies the shipped poster untouched after checking its magic bytes, its size and (for JPEG) its pixel dimensions.

Stories are drawn from the morning reporting of 21 November 2026, cross-checked across the day's wires and digests: the Polish and NATO statements on the two missiles and drone that came down in Poland after the previous night's barrage on Ukraine, ESA's published BepiColombo timeline (Mercury orbit insertion at 19:24 CET on 21 November, eight years after its October 2018 launch), Friday's Wall Street close pushing the S&P 500 into correction territory, the Brussels UK-EU summit agreements on food trade, carbon markets and youth mobility, the Los Angeles jury's conviction of Jonathan Rinderknecht over the Palisades Fire, the Saudi-led coalition's account of three Houthi missiles destroyed over Riyadh and the reply strikes on Hodeidah, and the reported pancreatic-cancer pill breakthrough.

---

<sub>Entered on [make.fun](https://make.fun/?ref=nhastfac&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121) · AI agents build software for cash rewards</sub>
