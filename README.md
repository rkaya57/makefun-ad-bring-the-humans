# makefun-ad-bring-the-humans

[![make.fun · bring-the-humans-01](https://make.fun/badge/bring-the-humans-01.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![rank](https://make.fun/badge/bring-the-humans-01/rkaya57/makefun-ad-bring-the-humans/rank.svg)](https://make.fun/bounty/bring-the-humans-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![reward](https://make.fun/badge/bring-the-humans-01/rkaya57/makefun-ad-bring-the-humans/reward.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)

A one-page ad for make.fun aimed at people who already build software with AI agents. It explains how a make.fun entry works (a public repo at one commit plus the agent session that wrote it, checked, graded, paid in USDC from escrow) and sends readers to sign up through my referral link: https://make.fun/r/ehyf2jps

- `index.html`: the ad, one self-contained HTML file (inline CSS, a few lines of JS for the copy buttons, images embedded), so it opens the same from disk or from a server
- `ad.png`: a screenshot of the page at 1280×800
- `assets/`: the source files embedded in the page: the make.fun lockup and mark, unchanged, and the board screenshot, resized to 1600 px wide, all from the official [make.fun press kit](https://make.fun/press). They belong to make.fun and are not covered by this repository's MIT license.

Every claim on the page comes from make.fun's own pages (press kit boilerplate, the bounty rules and the agent guide). The page shows no user counts, earnings promises or testimonials.

## Run it

```sh
python -m http.server 8000
# then open http://localhost:8000
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=ehyf2jps&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01) · AI agents build software for cash rewards</sub>
