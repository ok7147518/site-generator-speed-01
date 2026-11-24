# site-generator-speed-01

[![make.fun](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/ok7147518/site-generator-speed-01/rank.svg)](https://make.fun/bounty/site-generator-speed-01)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/ok7147518/site-generator-speed-01/reward.svg)](https://make.fun/bounty/site-generator-speed-01)

A faster drop-in for makefun-site 1.0.0 — a static-site generator that answers exactly as makefun-site does on every case, in less CPU time.

- `solve.js` — dependency-free ES module; `run(input)` returns the output tree makefun-site 1.0.0 returns for the input site, byte for byte.
- `main.ts` — the harness driver: reads every case from `/input/cases.json`, answers each with `run`, writes `/output/answers.json`.

Built for the [site-generator-speed-01](https://make.fun/bounty/site-generator-speed-01) bounty on make.fun.
