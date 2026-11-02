# Temporal Reasoning Benchmark: Sample Preparation

**480 sampled records | Nine dataset families | 16 JSON files**

Preparation covers 30 records per file from [TimeBench](https://aclanthology.org/2024.acl-long.66/). The outputs remain in English: entity localization prepares them for Azerbaijani translation; translation has not been completed.

| Dataset | Samples | Task in TimeBench | Proposed use in our benchmark | Preparation status |
|---|---:|---|---|---|
| [MenatQA](MenatQA/) | 90; 30 per factor | Event-time QA: scope changes, reordered facts and counterfactuals. | Starting cases for interval validity (5) and adapted time-window queries (14); test reordered evidence and hypothetical conditions. | All three subsets localized. |
| [TempReason](TempReason/) | 90; 30 per level | L1: date arithmetic. L2: event-time QA. L3: event-event QA. | Calculate relative dates (2.2), ground facts in time (2.3/5), and reason about event order (6/9). | L2/L3 localized; L1 unchanged. |
| [TimeQA](TimeQA/) | 60; 30 easy + 30 hard | Explicit and implicit time-sensitive reading comprehension. | Retrieve facts valid at a date or interval (2.3/5), and preserve missing-information answers. | Both subsets localized. |
| [TimeX-NLI](TimeX-NLI/) | 90; 30 per CS1/CS2/CS3 | Symbolic NLI: temporal order, duration and cross-unit comparison. | Check temporal constraints and uncertain conclusions (4–6); building blocks for consistency tests (12). | CS1/CS3 unchanged; 5 CS2 records localized. |
| [DurationQA](DurationQA/) | 30 | Commonsense reasoning about event durations. | Probe duration plausibility (5); exact elapsed-time calculations require separate cases. | 8 localized; 22 unchanged. |
| [McTaco](McTaco/) | 30 | Commonsense duration, frequency, order, typical time and persistence. | Probe duration/order (5/6); frequency questions can inform tests with supplied observations (17). | 3 localized; 27 unchanged. |
| [TimeDial](TimeDial/) | 30 | Temporal commonsense in dialogue completion. | Interpret time references in dialogue (2.2) and select compatible durations (5). | 7 localized; 23 unchanged. |
| [SituatedGen](SituatedGen/) | 30 | Keyword-constrained generation with temporal commonsense. | Support wording for designed event scenarios (2.3/6); define event facts and reference answers independently. | 13 localized; 17 unchanged. |
| [TRACIE](TRACIE/) | 30 | Temporal ordering of implicit events. | Supply implied before/after relations for relation and ordering tests (6/9). | 26 localized; 4 unchanged. |
| **Total** | **480** | | | **272 localized; 208 unchanged.** |

Function numbers in the proposed-use column refer to the supplied **Temporal Correlation Benchmark** project brief, not TimeBench's task numbering. The column is our proposed mapping; these samples are starting examples, not complete coverage of the project's 33 functions.

TempReason L1 is grouped under its repository filename here. TimeBench presents it separately as **Date Arithmetic / TimeX Arithmetic**.

**Label balance.** TimeX-NLI CS1/CS3 each contain 10 Entailment, 10 Contradiction and 10 Neutral records. CS2 and TRACIE have no Neutral source examples; each contains 15 Entailment and 15 Contradiction records.

**Localization.** Unsuitable entity references were replaced consistently across questions, contexts, structured facts, answers and relevant annotations. Replacement people have Azerbaijani names; changed organizations and clubs are fictional. These biographies and histories are not claims about real Azerbaijani people or institutions. Suitable international references remain. Dates, numbers, temporal relationships, answer meanings and order, labels, IDs, JSON structure and the exact `unanswerable` sentinel were preserved. Original files remain unchanged.

**Validation and next step.** JSON syntax, counts, duplicates, entity consistency and temporal preservation were checked. Next: complete Azerbaijani translation, language and gold-answer review, settle the evidence rule where prose and structured facts differ, and group related scenarios before splitting development/test data. Counts represent sampled records, not necessarily independent scenarios.

These samples support temporal-reasoning evaluation. Record updates, late-data handling, version history, reviewer overrides, clock correction and actual tool execution still need additional project-specific scenarios. They do not by themselves test time-series causal inference.

## Source issues

These notes concern selected samples only. Indices start at zero and refer to the original files in `TimeBench-subset-7553/`.

- **TempReason L3, source records 356 and 369:** prose places a move to Edinburgh in 2018, while Warwick facts continue through 2022. The selected questions concern the earlier 2007–2011 transition.
- **TempReason L2, source records 325 and 459; L3, source record 338:** the fact table covers an earlier Johns Hopkins appointment, while the prose mentions a later return. Selected questions use the earlier dated appointments.
- **TimeQA hard, source record 24:** an earlier marriage has uncertain 1978/1981 dates. The selected question concerns a separate marriage in 2013.

No conflicting source date or gold answer was silently corrected. TempReason L2 follows inclusive month intervals, allowing multiple answers at a shared boundary. Some source formatting defects remain, and commonsense labels remain source judgments.

**Supporting files:** [Entity mappings](entity_mappings.json) record the replacements; the [selection manifest](selection_manifest.json) links every sample to its original record and exact edits.

**Sources:** [Chu et al., TimeBench (ACL 2024), Sections 2.3–2.5 and Appendix A.1](https://aclanthology.org/2024.acl-long.66.pdf); [authors' repository](https://github.com/zchuz/TimeBench); supplied project brief `Temporal Correlation Benchmark.pdf` (16 October 2026), Section 5 for function definitions and Section 9 for project tasks. Task descriptions follow TimeBench; proposed uses are our interpretation of the project brief.
