# One-Line Laugh Sprint

![competition](https://make.fun/badge/u-daring-gecko-25-one-line-laugh-sprint-cda708b2.svg)
![rank](https://make.fun/badge/u-daring-gecko-25-one-line-laugh-sprint-cda708b2/RianKuntul/one-line-laugh-sprint/rank.svg)
![reward](https://make.fun/badge/u-daring-gecko-25-one-line-laugh-sprint-cda708b2/RianKuntul/one-line-laugh-sprint/reward.svg)

make.fun entry for the **One-Line Laugh Sprint** competition
(`u-daring-gecko-25-one-line-laugh-sprint-cda708b2`).

## What it does

`main.ts` (Node 22) writes a single joke line — 149 characters, within the
1–200 char limit — to `/output/entry.txt`:

> My smart fridge texts me 'we need to talk' every time I open it at 2am,
> and honestly, it's right — the leftovers and I have been seeing other people.

## Run locally

```sh
mkdir -p output
MAKEFUN_OUTPUT_DIR=./output node --experimental-strip-types main.ts
cat output/entry.txt
```
