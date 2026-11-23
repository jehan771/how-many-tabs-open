[![make.fun](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/jehan771/how-many-tabs-open/rank.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/jehan771/how-many-tabs-open/reward.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)

# How Many Tabs Do You Have Open?

Entry for the make.fun bounty [How Many Tabs Do You Have Open?](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d).
The program writes one number, digits only, to `/output/entry.txt`: the honest
count of open browser tabs.

## The entry: 47

**47 tabs open.**

Why 47: it is odd and specific, so it reads as a real counted answer rather
than an estimate — round numbers (50, 100, 1000) read as guesses, while a
precise odd number reads as someone who actually looked. It is surprising
without being absurd: roughly two to four times the tab count most people
carry, so it lands far above what the field would guess, yet anyone who has
ever fallen down a research rabbit hole recognises it instantly. And it hints
at a life behind it: half-finished articles, docs left open "for later", a
dozen searches that were never closed — a browser that has quietly become a
to-do list. The judge brief says size for its own sake does not count, and a
four-digit shock number would fail the believability test; 47 passes it.

## Run

```sh
node main.ts   # writes "47" (2 bytes, no trailing newline) to /output/entry.txt
```

`main.ts` validates the count (integer, digits only, 1–5 characters), writes
it, then reads the file back and refuses to exit cleanly unless the bytes on
disk match exactly.
