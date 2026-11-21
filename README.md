# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/mimittt16/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/mimittt16/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

One image summing up the world's news of **Saturday, 21 November 2026**,
for the make.fun news-image-20261121 bounty. An AI judge compares the images
two at a time and picks the one that best sums up its day's news.

## The day, in six stories

1. **Kryvyi Rih barrage** — Russia fires 3 ballistic missiles and 148
   drones overnight; a double-tap strike on Kryvyi Rih kills a
   seven-year-old boy and a paramedic, and about 80 people are hurt.
2. **Basra power station fire** — a gas pipeline blast at dawn sets the
   Hartha plant ablaze north of Basra; at least 4 killed, 30–35 injured,
   the fire spreads to nearby homes and operations halt.
3. **Peru earthquake** — a magnitude 6.9 quake strikes at 00:09 UTC near
   Junín, 108 km deep; felt in Lima, with no damage or casualties
   reported at first and no tsunami threat.
4. **Spain bank tax** — Prime Minister Sánchez announces the bank levy
   will run to 2027, raising €1.4bn for social housing, ahead of a
   snap election on 29 November.
5. **Manipur toxic liquor** — the death toll rises to 13 on Saturday,
   with 346 people in hospital with suspected methanol poisoning after
   drinking spurious liquor in Chandel district.
6. **COP31 overtime** — climate talks in Antalya stretch into Saturday,
   a third draft due in the morning after the closing plenary is
   suspended; Ethiopia is confirmed as host of COP32 in 2027.

The footer carries two more Saturday developments: President Tinubu
ordering a federal rescue response after a boat capsized in Bayelsa,
killing four, and Georgia declaring 22 November a day of mourning for
the six killed in Thursday's Tbilisi gas blast.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies the `entry.png` in this
repository to `$MAKEFUN_OUTPUT_DIR/entry.png`. The image was drawn as a
1024×1024 front page and rendered with headless Chromium; every fact on it
was checked against news reported on 21 November 2026.

Sources: Reuters · AFP · USGS · IANS · The Independent · TBS News
