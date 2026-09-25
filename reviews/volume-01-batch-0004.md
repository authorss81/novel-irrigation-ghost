# Review — Volume 01, Batch 0004 (Chapters 31–40)

**Reviewed:** the external review in `logs/batch-0004.review.log`, sixteen findings, against Chapters 1–40, the bible, the volume outline and all six state files.
**Passes:** the writer's own pass, the writer's repair pass, the external review, and **this fix pass**.
**Result: 16 findings, 15 real and fixed, 1 checked and not a fault. No chapter restarted, no scene replaced, no planned beat moved.**

---

## What the review found and what happened to it

| # | Finding | Severity | Outcome |
| --- | --- | --- | --- |
| 1 | The cistern held two incompatible histories | **BLOCKER** | Fixed — the missing water is now on the page and the claim is narrowed |
| 2 | Ch 34's inflow rate contradicted its own window | arithmetic | Fixed — 05:30 → 04:50 |
| 3 | *Sixteen days* wrong against the stop date | arithmetic | Fixed — one convention, stated once, applied everywhere |
| 4 | Ch 38 misquoted consultation 34 | continuity | Fixed — time and series restored |
| 5 | Ch 38's *forty-five days* not derivable | continuity | Fixed, and at source in Ch 30 |
| 6 | Ch 36 contradicted itself in one speech | continuity | Fixed — the stone is dated |
| 7 | Ch 33 scrambled Coll Preece's three days | continuity | Fixed |
| 8 | Ch 40's sheet dated the 27th, read on the 26th | continuity | Fixed — the sheet is the 26th |
| 9 | Ch 40's *for a fortnight* survived the repair pass | continuity | Fixed — seven days |
| 10 | The fourth-point tally disagreed three ways | arithmetic | Fixed in two chapters, plus two slips of the same kind |
| 11 | Ch 39's Ondra had no cause for his sleeplessness | continuity | Fixed — the 30th of the month before |
| 12 | Ch 32's orphaned fragment and unbalanced marks | prose | Fixed, and three more files with the same fault |
| 13 | `batch-0005` *Fifteen days from the 27th* | next phase | Fixed — sixteen and nineteen |
| 14 | `batch-0005` *four days long* / *the twelfth to the fifteenth* | next phase | Fixed — seven days, the 9th to the 15th |
| 15 | `batch-0005` says ref. 118 was spent in Ch 27 | next phase | **Not a fault. Checked and left alone** |
| 16 | `batch-0004-summary` dates and word list | state | Fixed |

---

## The BLOCKER, and the shape of the fix

**The finding.** `ch32:125` had Niko Venn say the tank was *four thousand seven hundred on the second*. `ch21:35` and `ch26:61` independently confirm 4,700 at the lip on the night of the 2nd, and `ch31:3–7` and `ch34:84` have the tank losing 120 gallons a day. 4,700 → 950 in twelve days is 312 a day. `ch34:100` has Yara Sen **swear** to 120/day in a filed statement. A reader can do the sum in ten seconds and the batch's load-bearing derivation does not close.

**Why it was not fixed by moving a number.** Every endpoint is already fixed by an earlier batch: 4,700 on the night of the 2nd, 1,950 on the 9th, 950 on the 14th. The 120/day decomposition is the batch's whole mechanism — 70 to mouths carrying salt, 50 to the sun leaving it. Moving any of them breaks Batch 0003.

**The fix.** The gap is real water and it had to be *water that went out of the gate to strangers at sixpence a gallon*, which is already in the manuscript — `ch21:19` and `ch26:63` carry Bel Crale's sale book, 1,820 gallons over the 3rd to the 9th, and 90 gallons of fenner pails on the 4th. So:

- **3,750** gallons left the tank between the 3rd and the 14th. The yard's own two numbers account for **1,440**. **2,310 went out in other people's pails** with no keeper's book, because a tank at its coping in a district with no keeper has never had a keeper's book.
- **Niko Venn**, in a yard on the 18th, says he can show the day it stopped being 120 a day and has had a week on the sum and cannot finish it.
- **Yara Sen's slate and her sworn paragraph 4** are both narrowed to *a hundred and twenty is what I can account for*, and the slate gains a line on a stranger's pail carrying salt out of the tank.
- **Marda Ollan** does the other half of the sum aloud in a yard on the 21st and finishes it.

**What the fix is worth.** The chapter's argument is that a form asserted a cause nobody measured. It now also carries a tank whose water left by three doors and a yard that can only account for one of them. **The cistern with no keeper is now the volume's central unmeasured fact rather than an error sitting under a number** — which is what the ending needs, because the last page of Volume 1 has to leave the box reading *keeper, none held*.

---

## The day count, and the three numbers that are not interchangeable

The plant was suspended on the night of the 2nd and resumed at 20:20 on the morning of the 20th. **The days of no delivery are the 3rd to the 19th: seventeen.**

| Count | Value | What it is |
| --- | --- | --- |
| Days of no delivery | **17** (3rd–19th) | the stoppage |
| Days the district has drunk the discharge | 16 on the 16th, 17 on the 17th | the supply, counted from the 1st |
| The return's *twenty days of storage* | 20 | **the ration period, 1st to the 21st** |

Ch 31's *fourteen* on the 16th became **thirteen**; Ch 32's *fourteen* on the 17th and Ch 33's *seventeen* on the 20th were already right; **Ch 34's four *sixteen* became *seventeen***, including the one the writer's own repair pass claimed to have fixed and had not. The return's twenty is now **defined on the page as the ration period**, and Yara says in a yard that the office has put twenty and seventeen on one page, that both are correct, and that only one of them was ever measured.

**The convention is now written into `state/continuity.md`, `state/current.md` and `workspace/volume-01/batch-0005/PROMPT.md`** so it cannot be re-flattened.

---

## The stages are not the gallons

`ch34:69` read *four at four, which is sixteen* — a third-stage child is given four gallons, and a fourth-point child is not a thing in the derivation. `ch31:129` had the same slip as *five in that column who was four* when the column is five children **at two points**, which is what makes Ch 34's *one of those five* derivable. Both now name the stage and the allowance separately, and so do the summary, continuity and the next prompt.

Separately, `ch33:41` said *nine children* on the 20th. Petra Olask was struck from the column on the **16th**, so the corrected column is **eight** and every chapter from the 17th on says eight. The same line said *This is the eighteenth* while boiling the 20th's jar beside the 18th's; it now says the twentieth.

---

## Finding 15: checked, and not a fault

The review says ref. 118 was spent in Chapter 4, checked in Chapter 13 and recited in Chapter 38, and that `batch-0005` is wrong to say Chapter 27.

**Checked every occurrence of 118 in the volume.** It appears in Chapters 2, 6, 8, 17, 27, 38 and 39. In **6, 8 and 17 it is the year**. In **38 and 39 it is the head-count at three pints**. In **Chapter 2** it is named as a schedule entry and nothing is spent. **The reference is spent in Chapter 27** — `ch27:99` the pressure shadow reads 118, `ch27:117` the extract of closure entry 118, `ch27:139` Mara Quill's certificate of both. Chapters 4 and 13 are Mara's chapters and contain no 118.

**`batch-0005/PROMPT.md` was right and was not changed.** The only edit is a note that closure entry 118 is *named* in Chapter 2 and *spent* in Chapter 27.

---

## Prose: the orphaned fragment and four unbalanced files

`ch32:97` was a lowercase, unquoted line between two paragraphs of Nell Drust's speech, and the file's quotation marks did not balance. It is now a paragraph of her speech with a subject, a reason and a consequence — *you can put it on that slate and it does not oblige me to a drop* — and it sets up her demand four paragraphs later to have her own name on the slate instead of the girl's.

**Four files were leaving a speech open at the end of the chapter**: Ch 32 (Tarin's four-paragraph speech), Ch 33 (Yara's closing speech), Ch 36 (Marrow's bench-book speech), and Ch 32 again on Niko's line. All closed. **All ten chapters of the batch now have an even number of quotation marks.**

**Out of scope, recorded not touched:** Chapters 9, 12, 14 and 15 also carry an odd total. They are Batch 0001 files, outside this phase, and not altered.

---

## Files changed

**Chapters (9):** 0030, 0031, 0032, 0033, 0034, 0036, 0038, 0039, 0040. Chapters 35 and 37 needed nothing and were not touched.
**State (5):** `batch-0004-summary.md`, `chapter-summaries.md`, `character-state.md`, `continuity.md`, `current.md`.
**Next phase (1):** `workspace/volume-01/batch-0005/PROMPT.md`.
**Not touched:** `state/phase-ledger.json`, `scripts/`, `.github/`, `.opencode/`, `AGENTS.md`, and every other controller file. `state/open-threads.md` needed no change — nothing in the findings altered a thread.

**Length: 34,485 words against a 30,000 ceiling, 15% over.** The pass added 636 words, all of them the cistern's second history and Niko's unfinished sum. The overrun is larger than it was and is disclosed in the batch summary rather than hidden.

---

## What was deliberately not changed

No chapter was rewritten and no scene replaced. **The volume's climax is untouched**: the Ashgate visit, the Guild's report, the collapse, the examination, the posted hearing and the eleven-hour window all stand where `outline/volume-01.md` and the Batch 0005 prompt put them. **No new enemy exists and no name-debt payment was added.** The Ashgate marker stone's blank face is still blank and is still never cut. The power state is unchanged: Stage 2, Name, no route opened anywhere in Chapters 31–40, no Gauge panel, no window won.

**The one thing that did change in substance** is that the volume now has a named, checkable, unresolved deficit of **2,310 gallons** in its central object. That is arithmetic and characterisation, not a new rule about how water works, and it is recorded as canon change 28 so Batch 0005 inherits it rather than rediscovers it.
