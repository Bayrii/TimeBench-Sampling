# Temporal Reasoning Benchmark: Sample Preparation

**270 sampled records | Four verified dataset families**

Preparation covers 270 sampled records across four TimeBench dataset families. The saved outputs remain in English: entity localization is preparation for Azerbaijani translation, not completed translation.

| Dataset | Samples | Task in TimeBench | Proposed use in our benchmark | Preparation status |
|---|---:|---|---|---|
| MenatQA | 90; 30 per factor | Event-time QA: time-scope changes, fact-order disruption and counterfactual questions. | Reason over time windows, reordered evidence and hypothetical temporal conditions. | Entities localized in all three subsets. |
| TempReason | 90; 30 per level | L1: symbolic date arithmetic.* L2: event-time QA. L3: event-event QA. | Calculate dates, identify facts valid at a time, and answer before/after queries. | L2/L3 localized; L1 selected unchanged. |
| TimeQA | 60; 30 easy + 30 hard | Event temporal reasoning: explicit and implicit time-sensitive reading comprehension. | Retrieve the correct event/entity for a requested date or time interval. | Entities localized in both subsets. |
| TimeX-NLI | 30; 10 per label | Symbolic NLI: temporal order, duration and cross-unit duration comparison. | Test time-constraint logic, duration/unit conversion and underdetermined conclusions. | Selected unchanged; no entity replacement needed. |

**Localization.** Foreign people, places and institutions were replaced consistently with Azerbaijani personal names and fictional local settings across questions, contexts, facts and answers. Dates and numerical values were retained. Three dataset families have localization drafts; the two unchanged subsets are TimeX-NLI and TempReason L1. Fictional institutions and biographies are not claims about real Azerbaijani entities.

**Validation and next step.** Next: complete Azerbaijani translation, language and gold-answer review, and scenario-family deduplication. Some TempReason biographies conflict with fact_context; resolve the evidence source before testing. These drafts support temporal reasoning, not the full record-update/tool-use component of our project.

Name check: "MinAtac" is MenatQA. "CRAIL" could not be verified in TimeBench or the processed outputs. TimeBench lists TRACIE, but no sampled TRACIE output was verified here; it is excluded from the total.

* TimeBench reports TempReason L1 separately as Date Arithmetic (TimeX Arithmetic). Counts are sampled records, not necessarily independent scenarios.

**Sources:** [Chu et al., TimeBench (ACL 2024), Sections 2.3/2.5 and Appendix A.1](https://aclanthology.org/2024.acl-long.66/); [authors' repository](https://github.com/zchuz/TimeBench); project brief and saved preparation audits. The project-use column is our mapping.
