# Temporal reasoning samples for Azerbaijani localization

This repository contains **480 English samples from TimeBench: 30 records from each of 16 JSON datasets**. Selected entity references have been localized for later Azerbaijani translation. The text has not been translated.

## Datasets

The original data is in [TimeBench-subset-7553/](TimeBench-subset-7553/). Prepared samples are in [Sample/](Sample/), using the same dataset filenames. Each sample file is a JSON array.

| Dataset | Files | Records | Focus |
|---|---:|---:|---|
| [DurationQA](Sample/DurationQA/) | 1 | 30 | Event durations |
| [McTaco](Sample/McTaco/) | 1 | 30 | Everyday temporal reasoning |
| [MenatQA](Sample/MenatQA/) | 3 | 90 | Time scopes, reordered evidence and hypothetical conditions |
| [SituatedGen](Sample/SituatedGen/) | 1 | 30 | Statements using temporal keywords |
| [TRACIE](Sample/TRACIE/) | 1 | 30 | Implicit temporal relationships |
| [TempReason](Sample/TempReason/) | 3 | 90 | Date arithmetic and event timelines |
| [TimeDial](Sample/TimeDial/) | 1 | 30 | Temporal dialogue completion |
| [TimeQA](Sample/TimeQA/) | 2 | 60 | Questions about events at particular times |
| [TimeX-NLI](Sample/TimeX-NLI/) | 3 | 90 | Temporal entailment, contradiction and uncertainty |
| **Total** | **16** | **480** | |

## Preparation

Records were selected for clear evidence and situations suitable for later Azerbaijani translation. Unsuitable personal names, places and organizations were replaced consistently. Replacement people and organizations are **fictional**, and do not describe real Azerbaijani public figures or institutions. Suitable international references remain.

Dates, numbers, temporal relationships, answer meanings and order, labels, IDs, JSON structure and the exact `unanswerable` sentinel were preserved. Original source files remain unchanged.

JSON syntax, counts, duplicates, entity consistency and preservation of temporal information were checked. TimeX-NLI CS1/CS3 contain 10 records per label. CS2 and TRACIE have no Neutral source examples, so each contains 15 Entailment and 15 Contradiction records.

## Supporting files

These files explain the preparation; they are separate from the dataset arrays.

| File | Purpose |
|---|---|
| [entity_mappings.json](Sample/entity_mappings.json) | Original names and their localized replacements |
| [selection_manifest.json](Sample/selection_manifest.json) | The source record and entity changes for each saved sample |
| [Sample preparation README](Sample/README.md) | Proposed project uses, preparation status and selected-source limitations |

Manifest indices start at zero. For example, `output_index: 0` and `source_index: 9` mean the first saved sample came from the tenth record in the matching original file. `source_record_sha256` is a fingerprint of that original record; `edits: []` means it was copied unchanged.

Some selected passages retain source inconsistencies outside the queried period; these are noted in the [source issues section](Sample/README.md#source-issues). Original gold answers were not silently corrected. Commonsense labels remain source annotations, and related questions may share contexts across files, so these samples are not independent training and test splits.

## Source

Prepared from [TimeBench](https://github.com/zchuz/TimeBench), by Zheng Chu and colleagues. See the [TimeBench paper (ACL 2024)](https://aclanthology.org/2024.acl-long.66/) for the original benchmark.
