# Review — Volume 02, Batch 0004 (Chapters 81–90)

**Reviewed:** the external review in `logs/batch-0004.review.log` — six findings, plus the chapter-8 dead reckoning below — against Chapters 81–90, the volume outline, the Batch 0005 prompt and all six state files.
**Passes:** the writer's pass, a trim pass, a review-fix pass during writing, the external review, and **this fix pass**.
**Result: six findings, all six real and all six fixed. No chapter restarted, no scene replaced, no planned beat moved, and one word changed in the prose.**

---

## What the review found and what happened to it

| # | Finding | Where | Severity | Outcome |
| --- | --- | --- | --- | --- |
| 1 | `current.md` claimed an external review had been run and every finding fixed; the reviewer subagent had in fact failed to dispatch and the log is a fallback notice plus a re-run | `state/current.md:21` | **process** | Fixed in the state file — the claim now says what was run and by what. The wiring itself is `.opencode/agent/` and is not ours to edit |
| 2 | The eleventh of next month is a **Sunday** and Chapter 88 called it a Monday | `chapter-0088.md:103` | **BLOCKER for the climax** | Fixed — one word. Same wrong weekday had reached the Chapter 88 entry in `state/chapter-summaries.md`; both corrected |
| 3 | The *Days lost* column in the next-phase prompt carried the pre-review-fix figures, *eight / twenty-three and a half*, against the page's *twelve / twenty-seven and a half* | `batch-0005/PROMPT.md:50` | **BLOCKER for the climax** | Fixed, and the reason is now written into the prompt so it cannot be re-injected |
| 4 | The volume outline's calendar spine and movement table still put Chapters 71–100 on days the page had left behind | `outline/volume-02.md:18,19,78` | drift | Fixed — the outline corrected against the page, with the month-Chapters-81–100 weekday run added in full |
| 5 | *The requisition's answer is dated the seventh and was received on the third* — the clause hung off the wrong noun | `state/current.md:21` | state | Fixed — the requisition was received on the third, the answer was entered on the seventh |
| 6 | *29,179* for the batch word count, a transposition of *29,277* | `batch-0005/PROMPT.md:78` | next phase | Fixed, and re-measured |

## Two more found in this fix pass, in the same class as the six

7. **The next-phase prompt had lost a fact the earlier review-fix pass established.** Job 4 sent the four field books to Vellum without saying *how* or *when*, and the prompt nowhere carried that **the second book went on the Friday the fourteenth, alone, in a cart with nothing else in it, and not in the Friday-the-ninth cart with the card.** Chapter 83 states it in the open and the prompt is the first document the next writer reads. Carried into Job 4.
8. **The next-phase prompt named a month for the volume's closing image that the outline deliberately leaves unnamed.** It said *the date is the fifteenth of the month after next*, which contradicts the prompt's own fixed range (the fourteenth to the twenty-third of next month) and contradicts `outline/volume-02.md`, which ends the volume on *the notice's date is the fifteenth, and it is the fifteenth* and names no month. The invented sentence is gone and the image is back on the day after the window, which is the batch's last day. **This was not a plot change: the outline's sentence is untouched and remains the authority.**

---

## Finding 2, the one that was on the page, and why one word was the whole fix

**The finding.** `chapter-0088.md:103` read *"On the **Monday morning the eleventh** day of next month a line went into the column headed days lost…"*

**The evidence, and it is six independent places on the page.** Chapter 84 opens on the *Sunday* fourth; the fifth is a Monday in the same chapter; the sixth a Tuesday in 85; the seventh a Wednesday in 86; the eighth a Thursday and the ninth a Friday in 87; the tenth a Saturday in 88's own first line; **the eleventh a Sunday in Chapter 89's first line and again at 90:87**; the twelfth a Monday in 89; the thirteenth a Tuesday in 90's first line. The chain from the seventh is unbroken and the eleventh is a Sunday.

**Why it mattered more than a slip.** The line Sef Ordry gives away is the **fourth line of the *Days lost* column**, and that column is the volume's cost ledger and the sixth and seventh lines of it are the window and the day after. A date error in the column is the kind of thing the volume-close arithmetic pass reads as truth.

**Why nothing else moved.** The entry is dated *the tenth* in Perdie Ammid's hand and it is written on the morning after the room of twenty-six, so only the weekday of the writing was wrong. One word for one word: **the batch re-measures at 29,277 and the per-chapter counts in `state/current.md` are unchanged.**

## Finding 3, the one that would have cost the climax its column

The prompt's own load-bearing list said the *Days lost* column held *four and a half, five and a half, four and a half, one, and eight; twenty-three and a half days*. The page says **twelve** and **twenty-seven and a half** (Chapter 90, `state/current.md`, `state/batch-0009-summary.md`). The fifth line is the requisition's round trip, which the review-fix pass corrected from eight days to **twelve** — four there, four back, and four standing in a yard at Vellum with a wet coat on the seat. **The prompt was carrying the pre-correction figure of the very number the correction was about, and the prompt's own line about a sixth and a seventh line depends on the total.** Corrected, with the reason written in so the next writer knows it has already been argued once.

## Finding 4, the outline, and what was corrected and what was deliberately left

The outline ran a chain of its own — the first of the month a Friday, the first of next month a Monday — which is self-consistent and is contradicted by Chapter 80 on the page. **The outline is corrected, and corrected only where the page speaks.** The movement table now reads 111–124, 125–137 and 138–147, the spine says the same, and a third bullet gives the whole weekday run of the month Chapters 81–100 are written in, from the first a Thursday to the thirty-first a Wednesday, with the chapter each weekday is established in.

**What was left alone, deliberately.** The outline's own weekday line for the earlier month is unchanged, because **Chapters 56 to 60 are written on that chain** — a divergence already recorded in `state/continuity.md` and deliberately not repaired, since re-cutting a weekday in five finished chapters is a bigger injury than a documented fault. **The volume-close pass must not "fix" those five chapters to the outline, and must not put the old day numbers back into the table.**

## Verified sound, and checked rather than assumed

- **Word counts are exact.** `wc -w` = **29,277**; 2994 / 2107 / 2274 / 2867 / 3120 / 3367 / 3453 / 3235 / 2288 / 3572, matching `state/current.md` line for line, before and after this pass.
- **The arithmetic closes.** 6 in × ¾ in = 4½ sq in = a thirty-second of a square foot; × 7½ gallons a cubic foot × 3600 = **844**. 844 × 4.1 = **3,460**; 850 × 4.1 = **3,485**; the twenty-five gallons between them are on the page and are left unresolved on purpose, and the board may carry both.
- **Power discipline held.** No gauge panel (four spent, in Chapters 5, 10, 24 and 57, budget for a fifth is zero), no Stage 3, no second name debt, the collective ghost unused, nothing opened, named, moved or shut in Movement IV.
- **Every chapter lands on a completed beat.** No cut-off endings, no compressed summaries, no outline prose standing in for a scene.
- **Not a fault, checked twice.** `state/batch-0009-summary.md` for Volume 02 Batch 0004 is a global counter, not a misnamed file — batch-0008 was Volume 02 Batch 0003. The other `batch-0004` commits on `origin/novel-wip/batch-0004` are Volume 01 work from a previous day, and there is no collision.
- **Not ours to touch, and untouched.** `state/phase-ledger.json` still reads `phase-000-bootstrap` / `attempts: 0`, and `.opencode/agent/novel-reviewer.md` still declares `mode: subagent`. Both are pipeline-owned. **Finding 1's real fix is a wiring decision and is flagged, not made.**

## The standing note for the next pass

**Three of the six findings were a figure or a date that had already been corrected once and came back in a document written after the correction.** The pattern is not carelessness in the prose; it is state drifting out of the brief. **Anything corrected in a review has to be corrected in the next-phase prompt in the same pass, or the correction is worth nothing.**
