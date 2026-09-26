# Review — Volume 03, Batch 0001 (Chapters 101–110)

**Reviewed:** the external review in `logs/batch-0001.review.log` — six blockers, five non-blocking findings and two pipeline-owned notes — against Chapters 101–110, `outline/volume-03.md`, the Batch 0002 prompt and all seven state files.
**Passes:** the writer's pass, a repair pass, a second repair pass against the first external review, the second external review, **this fix pass**, and a verification pass over this fix pass's own output.
**Result: six blockers, all six real and all six fixed. Five non-blocking findings, all five fixed, with one deliberate exception inside finding 9. No chapter restarted, no scene replaced, no planned beat moved, and the volume's direction untouched.**

---

## What the review found and what happened to it

| # | Finding | Where | Severity | Outcome |
| --- | --- | --- | --- | --- |
| 1 | Mara's recount of the returns adds to **21 in a file of 19**; the tally woman had fixed the right partition eighteen lines earlier and the two earliest returns were put outside the nine that are in five hands | `chapter-0105.md:61` | **BLOCKER** | Fixed — the two earliest are the first two years of the oldest hand, the seven after them are in four hands. **Nineteen returns in seven hands, unchanged**, which is the figure the whole batch quotes |
| 2 | *by **Monday** a man with a carpenter was going to nail one across a door in a lane **two hundred miles off*** — the order is written and read out in the lane water on the Thursday, Monday is the return to the court, and the only mileage in the batch is sixty-one miles east | `chapter-0105.md:31` | **BLOCKER** | Fixed — the day and the distance are gone; the sentence now says a name in a box is a thing that travels and the only reason a man with a bar would ever stand in that lane is a line she wrote herself before lunch |
| 3 | **"It is Wednesday"** in a scene the chapter itself fixes as Thursday the twenty-ninth at six separate places; a new line from the second repair pass | `chapter-0106.md:111` | **BLOCKER** | Fixed, with finding 4 |
| 4 | **A dropped promise created by the second repair pass**: Nesta names Wednesday morning for the stick test, and Wednesday is the chapter at Vellum; the test is staged on Thursday and no file owned the Wednesday | `chapter-0104.md:99` | **BLOCKER** | Fixed — the promise is for **Thursday**, the day Wick takes the reading and the day she keeps her word at the fourth trip |
| 5 | The certificate enters *unknown, estimated eleven including one infant of nine months* on the Wednesday morning, and the only paper carrying eleven is the Sunday count, which arrives in the **afternoon** bundle | `chapter-0105.md:17` | **BLOCKER** | Fixed — the persons box says **unknown**, with Mara refusing to invent a figure she was not given, and the afternoon's eleven lands beside it in her day-book |
| 6 | **The tank's recovery conflicts across volumes**: the outline said the mark came back three quarters of the inch and stands a quarter low; `chapter-0099.md` says on the page that it came back **the same inch in about a week**, and both the Tuesday and Monday readings still said 5⅞ | `outline/volume-03.md:60` | **BLOCKER** | Fixed, and **it gave to Volume 02** — see below |
| 7 | `current.md`'s only word-count section is Volume 02's batch: header 29,325, Volume 02 command, per-chapter figures 91–100 | `state/current.md:13` | state | Fixed — re-measured for this batch |
| 8 | *Last batch summary: `state/batch-0010-summary.md`* while line 7 declares Batch 0011 the last batch | `state/current.md:11` | state | Fixed |
| 9 | The close claims it created `workspace/volume-03/batch-0001/PROMPT.md` "and no other phase directory" while line 3 names `batch-0002/PROMPT.md` as next | `state/current.md:93` | state | Fixed — the sentence now names the prompt that exists. **The zero-byte `.wip-conflict` marker beside it was left alone**: it was put there by the pipeline's own `novel: skip stale WIP batch-0001` commit and is not ours to delete |
| 10 | The summary ended *No external review was run*, flatly contradicting its own lines 52 and 60 | `state/batch-0011-summary.md:5` | state | Fixed — the sentence now points at this file |
| 11 | **Attribution drift**: *eleven persons counted at six doors* is credited to **Wick's** stick reading, and Chapter 0106 calls it *Wick's count*, but it is **Corrie Lille's**, given door by door off his own hooks — and the scene's argument is that the count came from a hook and a head, not an instrument | `chapter-0105.md:67`, `chapter-0106.md:53` | fact | Fixed — the stick reading is Wick's, the count is Corrie's, in a second hand, on the same sheet |

## Two more found in this fix pass, in the same class

12. **The same chapter said the certificate *would go out with the Thursday bundle***, while the tally woman had tied it into the returns bundle on the Wednesday afternoon and said *it is in the bundle*. It went in on the Wednesday afternoon; it is the Thursday bundle that carries it to the Fair Copy. This is finding 2's day-confusion in the adjacent sentence.
13. **The Thursday lane figures could not both be true.** Chapter 0106 said the middle was *the same* in the afternoon and then that Wick's reading was *a third of an inch lower than his mark of that morning* — on a Thursday when Wick had not been to the lane at all. The afternoon figure is now a third of an inch in the middle and an inch at the edges, and the stick is read **against the same third doorstep Wick marked on the Tuesday morning**, which is where the test's authority comes from.

---

## Finding 6, the one that crossed a volume boundary

**The finding.** Volume 02's Chapter 99, on the page and after its own external review: *"the mark fell an inch in four hours and six minutes, and it had not finished falling, and **it came back the same inch in about a week**."* That sentence is in `chapters/volume-02/chapter-0099.md`, in `state/batch-0010-summary.md:125`, in `state/chapter-summaries.md:595`, in `state/volume-02-close-review.md:78` and twice in `state/continuity.md`. Volume 03's second repair pass had built the opposite fact — *came back three quarters of it, standing a quarter low* — into the outline, three state files, and six chapter lines.

**Why Volume 02 gave.** A closed volume's prose, externally reviewed and committed, governs a later one, and the arithmetic favours the same side: 6⅛ on the Thursday night, 5⅛ on the Friday morning is the inch; 5⅞ on the Monday the twenty-sixth and the Tuesday the twenty-seventh is three quarters of it back in four and five days; **6⅛ on the Thursday the twenty-ninth is the whole inch back in six days, which is what *about a week* means.** The Monday and Tuesday readings were never wrong and are untouched.

**What moved.** Chapter 0108's slate now carries *six and an eighth on the Thursday, and six and an eighth at every reading since, which is the whole of the inch back in six days, and nobody had written down anywhere in this valley that they had expected it.* Chapter 0110's closing catalogue reads *the tank stood at six and an eighth, back where it stood before the night of the twenty-second and no higher, with no rate* — which strengthens the catalogue, because the last line of that paragraph is that the only thing that moved in the valley all evening was a man with a pail. Chapter 0103 no longer says the mark *stopped* a quarter low; it says three quarters of it had come back by the Monday and that **a quarter of an inch is not a figure anybody can check**, which is a better reason for a man to climb a tank with a staff than a false one. The outline's rule line, `state/continuity.md` (three places), `state/open-threads.md` and `state/batch-0011-summary.md` carry the same figure, and the rule that survives from the second pass is the one that was never in doubt: **no chapter may call the fall half an inch.**

**The lesson worth keeping, and it is the reason this file exists.** The second pass was correcting a real error — two sentences and a state file said the fall was half an inch — and in correcting it wrote a *new* fact that contradicted a closed volume without noticing, because the number it was correcting was not the number that mattered. **A repair pass may not introduce a fact; it may only make the facts agree.** That is now written into the state files and it is why the tank's rule names the governing chapter rather than restating the figure alone.

## What the review checked and found correct on the page it read

- **Word counts were exact as the review read them.** `cat chapters/volume-03/chapter-010[1-9].md chapters/volume-03/chapter-0110.md | wc -w` = 29,049, per chapter 3102 / 3225 / 2810 / 2774 / 2790 / 3108 / 2588 / 2860 / 2934 / 2858. **This pass then changed six chapters, so those are the pre-pass figures; the post-pass batch is 29,299 and the per-chapter figures are in `state/current.md`, and they were re-counted rather than estimated.** None under 2,400, none over 3,600, and the batch is 206 under the 29,500 ceiling.
- **The prohibitions hold.** `this batch|the volume|an opening movement|the chapter|the reader` across 0101–0110: zero hits, before and after. No Gauge panel, no tea, no press, no ghost.
- **Calendar and day counts clean.** Tarin sixty-third to seventy-second, one per chapter. Water-day counts on the inclusive basis.
- **The repair method was the right one** — duplicated catalogue paragraphs were replaced with new scene, not reworded, which is why the batch grew rather than shrank.
- The volume outline's power-state note, the *midpoint not delivered early* flag on the ~Ch 125 turn, and Chapter 0110 keeping Mara ignorant of the count all stand.

## Third-pass verification, and the six things the fix pass caught in itself

**A verification pass was run over this repair pass's own output before filing, and it returned six things, all of them real and all of them fixed here.** The batch is now **29,299** words after all of it.

1. **`state/current.md`'s per-chapter list was stale** — it carried Chapter 105 at 2,928, measured before the last two edits to that chapter, so the ten figures no longer summed to the batch total. **Re-counted and reconciled against `state/batch-0011-summary.md` and `state/chapter-summaries.md`, which agreed with each other and with `wc -w`.**
2. **`state/open-threads.md:376` said the far-bank water was *nine* days old on the first of next month** where Chapter 0109 says **ten**, three times, on the inclusive basis every other file uses. **Now ten.**
3. **Two state files still described Nesta's promise as a Wednesday-morning one** — the exact sentence Blocker 4 removed — so `state/chapter-summaries.md` was describing Chapter 0104 two different ways. **Both now say Thursday evening.**
4. **`workspace/volume-03/batch-0002/PROMPT.md` said *Six more facts* and listed seven.** **The heading and its lead-in now say seven.**
5. **Two prose faults in the replacement text itself.** Chapter 0103's new clause collided with the clause already in the same sentence (*not a figure anybody can check* beside *a figure nobody will be able to check*), and **Chapter 0106 stated the lane's Thursday figures at line 53 and then had Wick measure and report the same figures at line 91 forty lines later** — the beat played twice, which is the duplication this batch's earlier passes were pruning. **The narration now says the middle holds better than the soft ground at the edges and leaves the numbers to Wick's reading.** Also removed: the doubled *put the pail down / set the pail down* gesture eleven lines apart, a three-clause sentence with a tense break in Chapter 0105, and a fourth *name in a box* in a chapter that already had three.
6. **Two pre-existing errors in files this pass edited.** Chapter 0104 said the lane was *up half an inch on Sunday*, which on the natural reading contradicts Chapter 0102, where the water fell from the ankle on the Saturday to the top of a boot on the Sunday; **it now reads *half an inch above Sunday's*, which is what Chapter 0104's own morning measurement says.** And `state/character-state.md` dated Dorrin's day-book copy to *the Wednesday the twenty-seventh*, when the twenty-seventh is a Tuesday. **Now the twenty-eighth.**

## Pipeline-owned, flagged once and not edited

- `state/phase-ledger.json` still reads `currentPhase: phase-000-bootstrap, status: planned` with eleven batches committed, so the ledger cannot be used to locate the phase.
- `workspace/volume-03/batch-0001/.wip-conflict`, a zero-byte marker left by the pipeline's own `novel: skip stale WIP batch-0001` commit.
- This file is the durable artefact the review gate asked for; before it, the second review existed only as three paragraphs inside `state/` files and the log.
