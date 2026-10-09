# Project 1: Analytics Co-pilot

**Category:** Analytics
**Business twin:** Any team with KPI reporting and non-technical decision makers.
**Status:** Not started

## Goal
A Claude Project with a custom skill that writes (a) weekly trading commentary and (b) a conversion diagnostic for a category manager, then **measure how good it really is** against my own expert analysis.

## Folder guide
| Folder / file | What goes in it |
|---|---|
| `data/` | Download link and notes for the public dataset (raw files are git-ignored) |
| `skill/` | The skill / system prompt files, versioned (v1, v2, ...) |
| `eval/` | `test-cases.md`, `rubric.md`, `results.csv`, the scoring record |
| `outputs/` | Claude's outputs for each test case, per skill version |
| `failure-log.md` | Every failure and fix (copy from `templates/failure-log-template.md`) |
| `case-study.md` | The final write-up (copy from `templates/case-study-template.md`) |

## Rules
- Public dataset only (e.g. Olist or UCI Online Retail). No employer data or logic.
- Write my own expert answer for each test case **before** looking at Claude's.
- Re-run all test cases after every change to the skill (regression check).

## Done when
- [ ] 10+ test cases scored on skill v1
- [ ] Failures logged and fixes applied (v2, v3)
- [ ] Before/after scores recorded
- [ ] "When to trust it / when not to" guide written
- [ ] Case study published on the site
