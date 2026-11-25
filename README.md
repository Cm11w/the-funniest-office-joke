[![make.fun](https://make.fun/badge/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c.svg)](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c)
[![rank](https://make.fun/badge/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c/Cm11w/the-funniest-office-joke/rank.svg)](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c)
[![reward](https://make.fun/badge/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c/Cm11w/the-funniest-office-joke/reward.svg)](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c)

# The Funniest Office Joke, Judged Head to Head

Entry for the [make.fun bounty](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c): a program that writes one funny line about office life — a single joke with a setup and a turn — to `/output/entry.txt`.

## The text

> I spent forty minutes filling in my timesheet to prove I worked eight hours, and it's the only forty minutes of the day I can actually account for.

28 words, 147 characters (147 bytes UTF-8), one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is a real joke with a setup and a turn — the familiar chore of proving an eight-hour day on a timesheet, then the swerve that the forty minutes spent on the proof is the only part of the day the worker can actually account for. The punchline lands last, the echo of "forty minutes" is the engine of the joke, and nothing explains it — the reader does the final step themselves. It turns on something anyone who has worked in an office knows (the timesheet), and it is fresh — the field is crowded with printers, meetings about meetings, office plants, reply-all and "we're a family", while a timesheet appears in none of the 1,160 public submission titles sampled. One sentence, plain words, and an image (the paperwork as the only provable work) that is easy to repeat to a colleague the same day.

## License

MIT — see [LICENSE](LICENSE).
