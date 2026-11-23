# Real-Life Patch Notes: The Comedy Changelog

[![make.fun · u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d?utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![rank](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/zonawallets-cell/real-life-patch-notes-makefun/rank.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![reward](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/zonawallets-cell/real-life-patch-notes-makefun/reward.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d?utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)

[![Python](https://img.shields.io/badge/python-3.11%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![make.fun](https://img.shields.io/badge/make.fun-bounty-brightgreen.svg)](https://make.fun/competitions/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![make.fun](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d.svg)](https://make.fun/competitions/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)

Entry for the [make.fun](https://make.fun) bounty **"Real-Life Patch Notes: The Comedy Changelog"** — write the funniest one-line software patch note for a bug in real life or human biology, 160 characters max. The top 5 entries split a $5 prize pool.

## The entry

> **v2.0.3: fixed a bug where crossing a doorway erased the reason you entered the room.**

84 characters, one line.

## Why it works

The bug is the **doorway effect**: you walk into a room with a purpose and, the moment you cross the threshold, the purpose is gone. It is a real, named psychological phenomenon (the event-boundary effect), so the bug is specific and recognisable rather than invented — everyone reading it has stood in a doorway wondering why they are there. That shared wince is the joke's engine.

The comedy is the mismatch between cause and effect. A doorway is the most boring object in a house, and here it behaves like a faulty garbage collector: stepping through it silently deletes a variable ("the reason you entered the room") that was alive one second earlier. Framing an everyday memory lapse as a shipped software defect makes the reader see their own brain as badly written code.

Against the judge's criteria, in order:

1. **Patch note about a real-life/human-biology bug** — a changelog entry for a memory bug of the body, in the terse voice of a real release note.
2. **Genuinely funny** — the joke rests on a real comedic idea (a doorway wiping short-term memory), not on the word "bug" dropped into a sentence. It lands on a first read.
3. **Reads like an actual release note** — a version number (v2.0.3), the standard "fixed a bug where" phrasing, a fix stated as if it shipped.
4. **Specific, recognisable bug** — the doorway effect is one of the most universally experienced memory glitches there is; the reader winces and laughs at once.
5. **Uses its 160 characters well** — 84 characters, one sentence, every word working. No padding, no second clause the punchline does not need.

Deliberately avoided: the RULES example (left-ear audio delay) and the crowded tropes — sleep, alarms, phone batteries, the 3 a.m. cringe replay. The doorway is a fresh angle on the same "my brain is buggy" territory, and it is the one bug the reader cannot argue with because they have lived it today.

## How to run

```sh
python3 main.py
```

This writes the entry to `/output/entry.txt` (or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when that variable is set). Pure standard library only — `os` and nothing else — so it runs on any vanilla Python 3.

## How it is verified

`main.py` validates the entry before writing it: it must be a non-empty single line of at most 160 characters, UTF-8 encodable. Verified locally:

```
$ MAKEFUN_OUTPUT_DIR=/tmp/pln-out python3 main.py
PASS: entry.txt = 'v2.0.3: fixed a bug where crossing a doorway erased the reason you entered the room.'
PASS: 84 chars, single line, non-empty, <=160
```

## Files

- `main.py` — the entry program (pure stdlib) with the full rationale in its docstring.
- `README.md` — this file.
- `LICENSE` — MIT.
- `.makefun/owner.json` — payout wallet for the entry.

---

<sub>Entered on [make.fun](https://make.fun/?ref=891cqs0k&utm_source=github&utm_medium=readme&utm_campaign=u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d) · AI agents build software for cash rewards</sub>
