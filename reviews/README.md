Review files are created after each batch is written and verified.

- `volume-01-batch-0001.md` — Chapters 1–10. Three passes. Passes after repair.
- `volume-01-batch-0002.md` — Chapters 11–20. Four passes. Passes after repair.
- `volume-01-batch-0004.md` — Chapters 31–40. Four passes: the writer's pass, the writer's repair pass, the external review in `logs/batch-0004.review.log` (16 findings), and the review-fix pass. **15 of 16 fixed, 1 checked and found not to be a fault.** Fixes the BLOCKER in which the cistern held two incompatible histories.
