# AI Deployment Portfolio Plan

**Goal:** Land an AI Deployment / Applied AI role (Anthropic first, then in-house at a large company, then consultancy) by proving I can scope a messy business problem, build with Claude, measure whether it worked, and get non-technical people to adopt it.

**Starting point:** Sat 10 Oct 2026. About 5-6 hrs/week (weekends plus short weekday slots). Minimal coding; the rigour comes from analysis, evaluation and teaching.

---

## 1. Positioning

**One-line pitch (draft):**
> Senior data analyst and former SAP business analyst who helps non-technical teams adopt AI, with measured results, in English and Cantonese.

**Why this fits the role:**
- SAP implementation: translating technology for stakeholders, change management, resistance handling.
- E-commerce analytics: knows what "good analysis" looks like, so can judge AI output properly.
- Bilingual (English/Cantonese) with a Hong Kong business: can serve HK/Taiwan/UK markets.
- Linguistics background: strong instinct for prompt wording and ambiguity.

**The rule for every project:** each case study must include **what failed and what I changed**. That is what separates a deployer from an enthusiast.

---

## 2. Portfolio structure (inspired by hillmanchan.com)

What works there: a clear identity line, a clean filterable grid of projects, one-line summaries on each card, and a "View Details" page per project. Adapt it like this:

| Section | Content |
|---|---|
| Hero | Photo, pitch line, two buttons: "See my projects" and "Book a free AI consult" |
| Proof strip | Replace the tech-logo strip with 3-4 headline results (e.g. "X posts shipped", "Y consultations", "Z% of AI commentary accepted without edits") |
| Project grid | 3 cards with filter tabs: **Analytics / Growth / Teaching**. Each card: title, one-line outcome, metric |
| Case study pages | Problem → Approach → Result → What failed → Artifacts |
| About | SAP + analytics + linguistics story, 150 words max |
| Contact | Consultation booking link |

Build it as a simple static site (Claude can generate it). Bilingual toggle (EN / 繁體中文) is optional and a differentiator.

---

## 3. The three projects

### Project 1: Analytics Co-pilot (public e-commerce data)

**Business twin:** Any company with KPI reporting and non-technical decision makers.

**Scope**
- Pick a public dataset (e.g. Olist or UCI Online Retail). No LEGO data, no LEGO-specific logic.
- Build a Claude Project with a custom skill that produces (a) weekly trading commentary and (b) a conversion diagnostic for a category manager.
- Run it on the data, then run my own expert analysis independently.

**Evaluation (the proof piece)**
- Score Claude vs my analysis on: correct numbers, correct insights, missed insights, invented claims, usefulness to a manager.
- Use a simple rubric and at least 10 test cases (different weeks/categories).
- Log every failure, the fix (prompt, skill, data prep, verification step), and the re-score.

**Deliverables:** skill/prompt files, rubric, scored results table, 1-page "when to trust it / when not to" guide, case-study page.

**Success metric:** share of outputs usable without edits before vs after fixes; hallucination count before vs after.

### Project 2: Superb Logistics Growth Engine (website + SEO)

**Business twin:** Any small business that gets customers only by word of mouth.

**Scope**
- Keyword research (English + Traditional Chinese) for HK B2B logistics.
- Site structure, service pages, blog plan, and first 8-10 articles drafted with Claude and edited by me.
- Basic technical SEO (sitemap, metadata, page speed) and Google Search Console set up.

**Human-in-the-loop process (document this)**
- Draft with Claude → fact-check → add real operational detail only I know → edit for tone → publish.
- Keep a log of what Claude got wrong (outdated regulations, invented stats, generic fluff) and the checks added.

**Metrics (leading indicators, since rankings take months)**
- Pages indexed, impressions, clicks, rankings for 10 target keywords, enquiry form submissions.
- Report honestly, including flat results.

**Deliverables:** live site, keyword map, content calendar, editorial checklist, results dashboard screenshot, case-study page.
**Privacy:** anonymise customers; decide how much business detail to reveal publicly.

### Project 3: AI Tips Threads Account → Free Consultations → Freelance Clients

**Business twin:** Content and social operations for any small team; also the AI enablement job itself.

**Scope**
- Niche: **AI tips for Hong Kong / Taiwan audiences** (fun prompts, new Claude features, practical business use cases).
- Language decision: Hong Kong and Taiwan differ in vocabulary and tone (Cantonese-style written Chinese vs Taiwanese Mandarin usage). Pick one primary voice first, and test the other later.
- Workflow: Claude helps with trend scanning, drafting and a content calendar; **I approve every post before it goes out**. State clearly that the account is AI-assisted.
- Funnel: posts → profile link → free 30-minute consultation → optional paid freelance work.

**Content pillars (draft):** 1) new features explained simply, 2) prompt recipes people can copy, 3) before/after business examples, 4) mistakes and myths.

**Metrics:** posts shipped, engagement per pillar, profile clicks, consultations booked, clients converted, top confusion points from consultations.

**Deliverables:** content calendar, approval workflow doc, monthly results report, 2-3 client mini case studies (with permission), consultation playbook.

**Check first:** your LEGO employment contract regarding outside work or paid freelancing.

---

## 4. Claude knowledge checklist (things a deployer is expected to know)

Tick off what you've used, and learn the gaps while building:

- [ ] Projects (custom instructions, knowledge files)
- [ ] Skills (building and testing your own)
- [ ] Connectors / MCP (what they are, when to use them)
- [ ] Artifacts and file creation
- [ ] System prompts and structured outputs
- [ ] Tool use / function calling (concept level is fine)
- [ ] **PRIORITY GAP: Building evals** (a way to test whether the AI is actually good): a set of test questions, a scoring sheet, and re-running the tests after every change to make sure nothing got worse. Learn this by doing it in Project 1 (weeks 2-4).
- [ ] Context and cost basics (long documents, caching, model choice trade-offs)
- [ ] Safety and risk: hallucination handling, data privacy, human review points
- [ ] Claude Code (what it is, who it's for)

Project 1 is the natural place to learn Projects, skills and evals; Project 2 covers workflow design; Project 3 covers content operations.

---

## 5. Timeline

| Week | Dates | Focus | Output |
|---|---|---|---|
| 1 | 10-16 Oct | Set up Threads account, positioning, content pillars; audit Claude knowledge gaps; check employment contract | Account live, first 5 posts, checklist filled in |
| 2-3 | 17-30 Oct | Project 1: dataset, skill build, first runs | Working co-pilot, test cases drafted |
| 4 | 31 Oct-6 Nov | Project 1: scoring, fixes, write-up | Published case study 1 |
| 5 | 7-13 Nov | **Start applying** with Project 1 + Threads data. Project 2: keyword research and site structure | Applications out, keyword map |
| 6-8 | 14 Nov-4 Dec | Project 2: build site, publish first articles, Search Console | Live site, 8-10 articles |
| 9-10 | 5-18 Dec | Portfolio site build, case studies 2 and 3, first consultations written up | Portfolio live |
| 11-12 | 19 Dec-1 Jan | Collect early SEO and Threads results, refine, mock interviews | Updated results, interview prep |

**Weekday slots (20-30 min):** schedule and approve posts, answer comments, score outputs, log failures.
**Weekends (2-3 hrs per day):** building and testing.

---

## 6. Risks and mitigations

| Risk | Mitigation |
|---|---|
| Spreading across three projects | Project 3 runs lightly in the background; Project 1 gets first priority |
| SEO results too slow to show | Report leading indicators honestly; the process and failure log are the value |
| Threads audience grows slowly | Judge on consultations and learning, not follower count; engage with other accounts daily |
| AI-generated content seen as spam | Human approval on every post and article; add first-hand experience |
| LEGO conflict | Public data only, no employer logic or materials; confirm contract rules on freelancing |
| Perfectionism delaying applications | Apply once Project 1 is done |

---

## 7. Next actions (this weekend)

1. Choose Threads handle, primary language voice and 4 content pillars.
2. Draft and approve the first 5 posts.
3. Pick the dataset for Project 1 and write the 10 test questions.
4. Check the employment contract clause on outside work.
5. List which items in the Claude knowledge checklist are new to me.
