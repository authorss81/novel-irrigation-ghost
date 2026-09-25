# Review — Volume 01, Batch 0002 (Chapters 11–20)

Reviewed against `AGENTS.md`, `outline/volume-01.md`, and the state files. Findings taken from `logs/batch-0002.review.log`; all repairs applied in place.

**Status: PASS after repair, two passes.** The first was the writer's own verification pass. It checked continuity against canon and reported no blocking defect. **That report was wrong, and the second pass is why:** it found six blocking defects, every one of them arithmetic or bookkeeping, and ten items worth fixing, plus four errors in the state files. No chapter was rewritten, no beat was moved, and the plot, the ending, the antagonist ladder and the volume's promise are untouched.

---

## Pass 1 — the writer's verification pass, and why it missed

It ran the mechanical checks that catch *repetition* — forbidden terms, real-software jargon, the `5·89` notation split, the marker stone's two faces, the two-finger press, duplicated paragraphs, repeated paragraph openers, the unconfirmed collective voice, no Gauge panel anywhere in the batch. All of those passed and all of them still pass.

It did not catch *addition*. Every blocking defect was a sum written in the same breath as its inputs, and nobody had done the division.

> **The rule this established, and it is the one to carry: a number a character dares a reader to check has to survive the check.** Chapter 15 says outright that its arithmetic can be verified by anybody in the yard with a stick and a string. Chapter 18 is a physician's ledger. Both now add up.

## Pass 2 — the independent review

### Blocking

**B1. The evaporation arithmetic was mutually impossible, and the text invited the reader to check it.** `chapter-0011.md:101` gave a quarter-inch a day, "in nine days is two inches, which is four hundred gallons" — about 44 gal/day. Two pages later `:125` gave "Two hundred and seventy gallons a day… A hundred and forty days," a 6× disagreement, and 140 × 270 is 37,800 gallons against a district that holds 6,700 in total. Chapter 15 reused it, and `state/continuity.md` canonised the wrong rate and the next-batch prompt propagated it.

**Fixed to one rate, derived on the page: 50 gallons a day out of the whole yard, and 6,700 over 50 is 134 days, spoken as *a hundred and thirty days*.** The per-inch figure is gone, because the yards have never been sounded and the rate is a measured one. Old Marden's "a hundred days" is now a guess Yara Sen corrects in front of the yard, and the check she invites the yard to make passes.

**B2. Chapter 18's money was out by an order of magnitude in both directions.** 680 gallons at 1d/2d/3d/3d tops out at £8 10s, not the £86 asserted. And £7 16s is 1,872 pence, which at 7–8d is 234 gallons, not the twenty-two asserted. The earlier repair pass had made Chapters 18, 19 and 20 *agree* with each other and still be wrong.

**Fixed from the day-by-day gallons, now stated on the page: 40, 40, 300, 300 at 1d, 2d, 3d, 3d. Ten shillings on the first eighty, seven pounds ten on the remaining six hundred, £8 exactly.** The dispensary now ends the month with **15s 4d**, which at 8d buys **23 gallons** — still "a third of one day", and now true. £8 in a lane where the dispensary runs a whole season on £41 is still a fortune, and it is still money that cannot buy the one thing for sale.

**B3. Chapter 15's clinic sum did not produce its own headline.** 4 × 4 × 14 is 224, not the stated fifty-six. 126 − 4 − 11 is 111, not "a hundred and fourteen". 70 × 14 is 980, not "five hundred". And the components summed to 27 gal/day against a stated 70.

**Fixed by deriving it out loud, which is what the scene is for:** four children in the third stage at 4 gallons, five in the second stage at 2 gallons, 117 others at a floor of three pints a head — **sixteen, and ten, and forty-four, which is seventy.** A fortnight of it is 980, rounded on the page to a thousand.

**B4. The mark counts contradicted themselves three chapters apart.** `chapter-0015.md:11` said nine names had the marks, four at all three points, and "Eleven had them at two" — fifteen. Chapters 16 and 18 both say nine.

**Fixed to four at three points and five at two**, and the stage language now matches: three marks is the third stage, two marks is the second, and the fourth stage is the one that kills and is not here. Every downstream reference re-derived from 4 + 5.

**B5. Pell's return described events that had not happened, on a fourth date.** `chapter-0020.md:55` dated it the seventeenth and its remark reports 6,700 gallons standing and the plate weeping — the water arrived 16:00 on the 20th, stopped at 03:00 on the 21st, and the floor came up on the 30th. Chapter 11 offered it for the 22nd; the state files said the 23rd.

**Fixed: the return is dated the twenty-second** and was carried into the district book on the 23rd with the returns, and the engineer's statement it records is the one from the yard on the 21st. The Day 17 date belongs to **folio eleven** going into restricted handling, which is a different document and a different event, and the two are now kept apart in `state/continuity.md`.

**B6. The handed-off prompt contradicted the last line of the previous chapter.** `batch-0003/PROMPT.md:42` opened with the thump "three a second… and **has never stopped**." `chapter-0019.md:137` ends on it stopping — "Not slowed. Stopped." — which is the chapter's closing beat and the reason Niko's next move exists.

**Fixed, and the stop is now canon** rather than a detail: it stops on the night of the 2nd, in the middle of Niko's hand on a coil of somebody else's rope.

### Should fix — done

| # | Finding | Resolution |
| --- | --- | --- |
| 7 | The descent was walked, but the brief also forbade walking it. The prose followed the card; the card was right. | `state/continuity.md` now says what Chapter 19 actually spent — **the mouth of the cut** — and what it did not: **going down past the staging**, which is Batch 0003's threshold beat. The dated spine and the do-not-re-stage list in the next prompt both rebuilt around the split. The prior batch's own prompt is a pipeline file and was not edited. |
| 8 | The reading day was the fourth, called a Thursday, eleven days away in one place and twelve in another, while Chapter 15 pinned the 27th as a Thursday. | **The month has thirty-one days.** Day 33 is Wednesday the 2nd, Day 34 is Thursday the 3rd, and the scheduled reading day is **the eleventh of the next month, a Friday — Day 42, eight days out**, which is also the date Batch 0003's Chapter 27 needs. Chapter 20's four references, the warden's note, the certificate's filing date and the prompt are realigned. The 4th of the next month survives only as Yara's marks fortnight, which is a different 4th. |
| 9 | The brackish tap was spent twice with two causes. | Chapter 15's foreshadowing now says the last dry tap has been *getting slower*; Chapter 31's brackishness stays the water table's doing. |
| 10 | The two-finger press was re-staged against a do-not-re-stage list. | Cut to one clause — *out of forty years of habit, and were not there.* The tin pot and the tasteless tea keep the beat, because they carry the new material (*he had hoped*). |
| 11 | Chapter 14's witness-list numbers did not add up. | The page shows three signing scenes, so the list is **three signers and two refusals**, and Pell's ground three, the dusk summary and the condition line all say three. Twenty-two households became **twenty-four**, and the tally is now 15 no plus 3 yes-conditional out of 18 asked. |
| 12 | `chapter-0015.md:85-91` read as a bulleted list of options under four bolded headers that mimicked a Gauge panel. | Rebuilt as a scene: Wick counts the wells and is talked out of a fourth, Bel speaks from under the awning, Marden shuts down the old well himself. **One** bolded header remains in the chapter, not four. |
| 13 | Yard crowds of 40, 80 and 200 in a district of 126. | **A hundred and twenty** for the two full-yard scenes, in Chapters 15, 18 and 20. The eighty-person figures are Batch 0001's Day 20 yard and were left alone, because Chapter 10 fixes them. |
| 14 | The next prompt was confused about volume and reveal. | Volume 4 is named correctly now, and the sentence distinguishes the **fact about a place** that Batch 0003 spends from the **identity** that a later volume keeps. Also fixed a duplicated word ("moved, moved, or held"). |
| 15 | ~24 paragraphs opened "That is…" and ~25 "And…"; "Tarin Rusk…" opened ten, three of them inside one chapter. | Sixteen openers re-opened. "And" paragraphs are down from 25 to 9, and every one of the nine is a document quotation or Chapter 19's closing beat. "Tarin Rusk…" is down to eight, at most two in a chapter. |
| 16 | The blue-book list was claimed trimmed and was still in full, and its *Witness* line pre-empted Chapter 14. | The **Witness line is gone** — Tarin does not yet know what he is looking for — and the list is six lines with five ticked. The last paragraph was tightened so it no longer restates what Chapter 14 goes on to find. |

### Two errors found in the course of the pass, and fixed

- **Chapter 12's petition added to 145 people in a lane of 126.** 22 signed, 19 declined, 104 never asked. Now **eighty-seven**, which gives 22 + 19 + 87 = 128 — the 126 counted plus the two entered at the margin. This also stops it colliding with Chapter 16's *hundred and four*, which is a different document: the struck strokes in the 125-year-old survey folio. The two are now explicitly kept apart in `state/continuity.md`.
- **Chapter 16's field book promised a list of a hundred and forty over a folio carrying a hundred and four.** Now a noticed gap rather than an error, and thirty-six missing strokes is the first thing in twenty-six years anybody in that lane is in a position to notice.

### State-file accuracy

| Claimed | Actual | Action |
| --- | --- | --- |
| 39,661 words | **40,142** as it now stands, 39,740 before the repair pass added its arithmetic | corrected; overrun now **29%** |
| "five points of view including two first-person chapters" | six points of view, **no first-person chapters** | corrected |
| tea tasteless "since the ninth" | **the seventh** (`chapter-0017.md:117`) | corrected in `current.md` and the next prompt |
| "eleven days" between the 17th and the 34th | **seventeen** | superseded; that interval no longer exists |
| the first pass "found no blocking defect" | six | corrected rather than left standing |

### Accepted, not changed

- **The length overrun.** Batch 0001 overran by 3% and Batch 0002 by 29%, and the batch kept its scenes. The brief calls the figure a budget for pacing and forbids cutting a finished scene to hit a number. The next prompt now carries the true figure and asks for a leaner half.
- **The Batch 0002 brief's do-not-re-stage list contradicted its own Chapter 19 card.** The prompt is a pipeline file and was not edited; the correction is recorded in `state/continuity.md` and carried into Batch 0003's prompt, which is the one a writer will actually read.
- **Chapter 17 remains the best thing in the batch** and is untouched: genuinely physical, genuinely expensive, and Tarin is refused the answer on the page.

## Verification results after Pass 2

| Check | Result |
| --- | --- |
| Ten finished scenes, no stubs or outlines | pass |
| No chapter ends mid-action or mid-sentence | pass |
| No duplicated paragraphs | pass |
| No meta or plan language in prose | pass |
| No forbidden terms in prose (*Blind Reservoir*, *One Map*, *Boryn Vey*, "the reservoir") | pass |
| No real-software jargon | pass |
| **Every stated sum re-derived from its own inputs** | pass (was fail on five figures) |
| **Calendar internally consistent across all four files** | pass (was fail: four dates, three weekday claims, two day-counts) |
| Petition totals to the district's own count | pass (was 145 in a lane of 126) |
| Witness list matches the signing scenes | pass (was three described as four) |
| Gauge panels | **zero in ten chapters** — the correct call, and kept |
| One bolded panel-style header, not four | pass (was fail) |
| 5·89 written in documents, spoken as words in speech | pass |
| Marker stone's blank face never cut | pass |
| Two charges distinct, dated, unjoined, unresolved | pass |
| Name debt still open and shown open, once, cheaply | pass |
| Collective voice unconfirmed; no character names it | pass |
| No new final threat; Bend not reached | pass |
| Yard crowds within the district's 126 | pass (was 200) |
| Paragraph-opener distribution | pass (was fail) |
| Card coverage | 10 full |

## The one thing the review got right about the brief

The Batch 0002 summary said a reviewer pass was still owed. It was, and the reason it was owed is now written down: mechanical checks catch repetition, not addition. Three numbers in this batch were carried from a plan or from a previous repair instead of derived from the sentence they sit in, and every one of them was caught only by someone doing the division out loud. That is a writing pass, not a grep, and it is the part that does not automate.
