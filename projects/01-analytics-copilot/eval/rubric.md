# Scoring rubric

Score each Claude output on five criteria. Score **0 = fail, 1 = partly, 2 = good**. Maximum 10 per test case.

| Criterion | 0 | 1 | 2 |
|---|---|---|---|
| **Numbers correct** | Key numbers wrong | Minor errors | All numbers match the data |
| **Insight quality** | Misses the main story | Finds some of it | Finds the main story I found |
| **No invented claims** | States things not in the data | One shaky claim | Every claim traceable to the data |
| **Useful to a manager** | Unclear or not actionable | Okay but generic | Clear, specific, actionable |
| **Tone and format** | Jargon-heavy or messy | Acceptable | Clear, concise, ready to send |

## Usable without edits?
Mark **Yes** only if I would send it as it is. Track the share of Yes answers per skill version.

## Hallucination count
Count each invented number, cause or claim separately. Track per skill version.

## Scoring record
Record every run in `results.csv` with these columns:

`test_case_id, skill_version, numbers, insight, no_invented, useful, tone, total, usable_without_edits, hallucination_count, notes`
