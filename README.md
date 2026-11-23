# site-generator-speed-01-run-20261122

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/aangrohim-cell/site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/aangrohim-cell/site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0. `solve.js` returns exactly the reference output tree for every case; it saves CPU time by escaping Markdown inline text in bulk runs instead of one character at a time, counting words without building an array of matches, trimming lines with charcode checks instead of a regex, and joining rendered blocks without an intermediate mapped array. `main.ts` reads `/input/cases.json` and writes `/output/answers.json`.

## Run it

```sh
node main.ts
```

The bundled `vendor/makefun-site/` is make.fun's own reference code (MIT), kept unchanged apart from the hot-path edits above.

---

<sub>Entered on [make.fun](https://make.fun/?ref=5r5csrph&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
