# Completed Factorio benchmark ledger

Compiled 18 October 2026. Evidence cutoff: 8 October 2026. Selected historical results, not an exhaustive inventory or a current model ranking.

| Experiment | Recorded model / effort | Observations | Result | Important boundary | Record |
|---|---|---:|---|---|---|
| Merge calibration, original 16-task set | gpt-5.6-terra / max | 16 attempts | 16/16 solved; 16/16 at best count; mean 1.000 | pi harness | A |
| Merge calibration, original 16-task set | gpt-6-sol / max | 16 attempts | 16/16 solved; 15/16 at best count; mean 0.996 | pi harness | A |
| Merge calibration, original 16-task set | DeepSeek Flash / max | 16 attempts | 15/16 solved; 10/16 at best count; mean 0.879 | One missing submission counts as zero | A |
| Merge calibration, original 16-task set | muse-spark 1.3 / xhigh | 16 attempts | 15/16 solved; 4/16 at best count; mean 0.822 | One missing submission counts as zero | A |
| Repeated hard merges | gpt-5.6-terra / max | 6 tasks × 3 | 18/18 solved; 8/18 at best count; mean 0.962 | Same six tasks repeated, not 18 unique tasks | A |
| Repeated hard merges | gpt-6-sol / max | 6 tasks × 3 | 18/18 solved; 8/18 at best count; mean 0.952 | Matched pi setup; small task sample | A |
| Hard merges, stopped batch | Fable 5.1 / max | 11/18 planned | 11/11 observed solved; 7/11 at best count; mean 0.964 | Claude Code; seven planned attempts unobserved | A |
| Hard merges, stopped batch | Opus 5 / max | 4 attempts | 4/4 solved; 1/4 at best count; mean 0.907 | Part of 10/18 observed batch; two replies capped | A |
| Hard merges, stopped batch | Opus 5 / high | 5 attempts | 5/5 solved; 0/5 at best count; mean 0.851 | Same stopped batch; uneven task exposure | A |
| Hard merges, stopped batch | Opus 5 / high → max | 1 attempt | Solved; above best entity count; score 0.825 | Effort changed during attempt | A |
| Vulcanus legendary basics, unboosted | Opus 5.5 / medium | 1 attempt | Partial, 0.4067; 6/18 product targets; 30.94% occupancy | Context leakage and deadline extensions recorded | A |
| Vulcanus legendary basics, unboosted | Opus 5.5 / high | 1 attempt | Partial, 0.5778; 10/18 targets; 80.34% occupancy | Product requirement failed; not a clean effort study | A |
| Vulcanus legendary basics, unboosted | Opus 5.5 / max | 1 attempt | Partial, 0.7083; 13/18 targets; 80.50% occupancy | Product requirement failed; not a clean effort study | A |
| Vulcanus legendary basics, reference-informed boosted | Sonnet 5.5 / high | 1 attempt | Partial, 0.5083; 15/18 targets; 20.72% occupancy | Extra kit and reference-informed lessons | A, D |
| Vulcanus legendary basics, reference-informed boosted | Sonnet 5.5 / xhigh | 1 attempt | Partial, 0.5500; 18/18 targets; 13.58% occupancy | Occupancy failed; no stability grade | A, D |
| Vulcanus legendary basics, reference-informed boosted | Sonnet 5.5 / max | 1 attempt | Partial, 0.5500; 18/18 targets; 16.41% occupancy | Occupancy failed; no stability grade | A, D |
| Vulcanus legendary basics, fair | gpt-6-astra / max | 1 attempt; 28 simulations | Recorded solve, 1.00; 18/18 targets; 80.3% occupancy; both recovery tests passed | Seed-1 grade; later seed diagnostics below narrow the conclusion | B, D |
| Later merge calibration | Fable 5.1 / effort unverified | 16 tasks | 15/16 at best count; mean 0.986875 | Different agent harness/toolkit from original calibration | D |
| Eight-task calibration extension | Sol 6.1 / effort unverified | 8 tasks | 8/8 solved | Separate model/version from gpt-6-sol; execution conditions not randomized | D |
| Eight-task calibration extension | DeepSeek / version and effort unverified | 8 tasks | 3/8 solved | Paired task set; execution conditions not randomized | D |
| Matched processing-unit occupancy experiment | Fable 5.1 / effort unverified | 1 selected run | 83.1 units/min; 80.4–80.6% occupancy; 26×19 cell | Passed by about two tiles; external power, end-game research | C |
| Matched processing-unit occupancy experiment | gpt-6-astra / effort unverified | 1 selected run | Best occupancy 73.3%; occupancy requirement failed | Same brief, lineage and lessons; one run per model | C |
| Frozen Vulcanus delivery diagnostic | Sonnet 5.5 max boosted design | 3 seeds, 1 hour each | All 18 targets each time; slowest product 1.017–1.067/min | 3–4 zero-delivery basket windows/hour; containers grew 13,756–13,926 items/hour; occupancy still failed | E |
| Frozen Vulcanus delivery diagnostic | Sonnet 5.5 xhigh boosted design | 3 seeds, 1 hour each | All 18 targets each time; slowest product 65/hour (1.083/min) | 2–4 zero-delivery basket windows/hour; containers grew 10,880–11,081 items/hour; occupancy still failed | E |
| Later Vulcanus seed diagnostic | Astra fair design | Seeds 1 / 2 / 3 | Products at target: 18 / 16 / 17; slowest rate: 1.000 / 0.467 / 0.333 per min | Output-only diagnostics; recovery tests not repeated | D |
| Later Vulcanus seed diagnostic | Astra reference-informed design | Seeds 1 / 2 / 3 | Products at target: 18 / 5 / 18; slowest rate: 1.033 / 0 / 1.067 per min | Separate from fair design; no new solve or stability grade | D |
| Later Vulcanus seed diagnostic | Fable fair design | Seeds 1 / 2 / 3 | Products at target: 16 / 15 / 15; slowest rate: 0.817 / 0.733 / 0.700 per min | Historical grade not restated here | D |
| Later Vulcanus seed diagnostic | Hidden reference design | Seeds 1 / 2 / 3 | Products at target: 18 / 18 / 18; slowest rate: 1.417 / 1.433 / 1.417 per min | Reference control, not a model submission | D |
| Later Vulcanus seed diagnostic | Sol 6.1 fair design | Seeds 1 / 2 / 3 | Products at target: 18 / 17 / 17; slowest rate: 1.017 / 0.700 / 0.933 per min | Historical grade not restated here | D |

Scores belong to their original tasks and grading rules. Merge “at best count” means the submitted solution reached the disclosed reference entity count; means include started-but-unsubmitted attempts as zero. Original merge runs allowed 60 minutes and three simulations each. Stopped schedules show observed submissions; unstarted plans are missing observations.

Vulcanus required 18 legendary products at ≥1/game-minute each and ≥80% occupancy. The fixture supplied boundary inputs, power and research, and permitted selected legendary equipment. “Boosted” rows are reference-informed and must remain separate from fair runs. Opus unboosted runs also have recorded context-leakage limitations. Diagnostics used Factorio 2.0.77, 20 game-minutes of warm-up and 60 measured game-minutes. The six-run robustness fixture included a custom control-only grader mod. They are finite output observations, not multi-seed recovery certification. A zero-basket window means at least one product had no delivery in that five-minute window.

Records: A = archived sweep digest assembled 3 October; B = completed-result report, 5 October; C = matched-occupancy report, 6 October; D = evidence recheck through 8 October; E = six-run robustness review, 4 October. Raw records, private locators, saves, designs and harness code are not included, so this ledger alone is not a runnable reproduction. Model labels are historical; unchecked settings are marked unverified. Curation: beckett-works; AI-assisted synthesis.
