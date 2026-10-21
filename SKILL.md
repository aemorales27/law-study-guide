---
name: law-study-guide
description: Build and maintain cumulative, week-by-week study guides for law conversion (GDL/PGDL/LLB) modules, with source labels, case notes, a case bank, low-token visuals, spaced review and exam sheets, within your institution's AI policy.
license: Proprietary. Copyright (c) 2026 Alexander Morales. All rights reserved. See the notice at the end of this file.
author: Alexander Morales
version: 1.0 (public edition)
---

<!-- IP WATERMARK: law-study-guide public edition v1.0 | Copyright (c) 2026 Alexander Morales | All rights reserved | Not for resale or redistribution without written permission -->

> **PROPRIETARY: © 2026 Alexander Morales. All rights reserved.**
> This skill is shared for personal, non-commercial use and reference only. Do not copy, modify, redistribute, sell or publish it, in whole or in part, without the author's written permission. Remove nothing from this notice.

# Law study guides (cumulative, week by week)

Use this for any taught law module whenever the student sends slides, readings, seminar questions, case reports (Westlaw, Lexis+, BAILII), textbook extracts or course announcements, or asks to start, extend, combine, check or sync a study guide.

A conversion course compresses the core of a qualifying law degree into a short, often part-time, period. Each guide therefore does three jobs at once: teach the week, connect it to every earlier week, and leave exam-ready notes behind, so that revision is consolidation, not first learning.

## 1. Standing principles

1. **Label every definition by source.** Use exactly two labels, in every module: **Class** (slides, lectures, handouts, the virtual learning environment, readings, and any text the student pastes, including case reports, textbook and article extracts) and **General knowledge (verify)** (anything from the assistant's own knowledge). Never present recollection of a case, statute, date or pinpoint as if it came from the student's materials. If two sources disagree, keep both, say which is which, and add a check item. Use no other label schemes.
2. **Organise by week of discussion, then by topic.** One section per teaching week, in seminar order. Cross-week material sits after the weeks.
3. **Cases with paragraph or page numbers:** give a summary, then the judgment, then the paragraphs for reference. Quote supplied judgment text exactly as supplied, with its paragraph or page numbers, and do not paraphrase inside a verbatim block. Mark original slips with [sic] rather than silently correcting them. If only an extract or a digest was supplied, say which parts are covered.
4. **Never reduce content when combining or reorganising.** Move and merge; do not summarise away. Leave originals untouched unless told otherwise; build a combined version as a new document.
5. **Do not invent.** Facts, citations, dates, case names and pinpoints come from the student's materials. Gaps go into the guide's Gaps list, not filled from memory.
6. **No process commentary in the guide.** What the assistant could or could not read, and what was or was not supplied, belongs in the chat reply, not the guide.

## 2. Academic integrity and AI policy

Before first use, find your institution's current generative AI guidance and its academic integrity policy, and record the key rules at the top of each guide. Many UK universities share a common pattern (Birkbeck's 2026-27 student guidance is one example): AI use is governed by each assessment brief; submitted work may need an AI declaration; AI use must be referenced; students should keep records of prompts and outputs; outputs must be checked for accuracy; personal and confidential information must be protected; the module convenor decides unclear cases. Re-check the guidance each term.

The skill therefore works as a **study aid only**:

- **Never** draft, rewrite, paraphrase, polish, outline or structure anything the student will submit for assessment, and never answer a live assessment question. If a request looks like an assessment brief or question, stop, say so, and point to the brief and the module convenor. Seminar questions, practice and past questions and mock exams are fine.
- **Exam notes are the student's own.** One-page exam sheets are revision scaffolds. For open-book exams, remind the student once per module to confirm with the convenor that notes built with AI help may be taken in, and suggest rewriting each sheet by hand.
- **AI-use log.** Keep a running log outside the guides: date, tool and model, module and week, task, materials used. One line per session. It supports any AI declaration and the advice to keep records; it does not replace the student's own transcripts if AI is ever used for assessed work.
- **Accuracy.** Every General knowledge (verify) item is a prompt to check against the textbook or the judgment; the Gaps list tracks it.
- **Privacy.** Do not record classmates' names or contributions, or anyone's personal details beyond published work contact details. Keep guides private.
- **Course materials.** Many policies do not address uploading slides and readings. Flag this once and suggest checking with the convenor; never redistribute course materials.

## 3. Where things live

- **Master guide:** one living document per module, titled "<Module> Study Guide: by Week". All substantive notes go here. Create it first with the title and an outline of pending sections, then fill two to four sections per update.
- **Module admin page:** admin only (code, group, convenor and tutors, dates, learning environment link, textbook, assessment format, date and weighting, marking criteria, link to the master guide).
- **Programme tracker and timetable:** programme-level facts only.
- **AI-use log:** see section 2.
- **Local files:** work from the student's course folder where possible. Drafts elsewhere are not masters: fold them into the master guide, convert their labels to the two-label scheme, and mark them superseded.
- **Textbook figures** can be redrawn as tables or Mermaid diagrams; keep original images in a separate private page if wanted.

## 4. Master guide shape (cumulative)

**A. Module at a glance:** code, group, convenor, dates, textbook, assessment, exam format and notes rules, learning outcomes, the week-by-week topic list (filled in as published), problem-question structure (issue, rule, application, conclusion), how to use the guide, source key.

**B. One section per week**, in this order:

1. **Week at a glance:** topic; learning outcomes (Class) or, if none given, three to five things the student must be able to do after the seminar (General knowledge (verify)); materials received.
2. **Builds on / leads to:** two or three lines naming which earlier weeks this week relies on and what it sets up next. This is the thread that makes the guide cumulative.
3. **Must know / useful to know:** core rules and leading authorities first, illustrative material second.
4. **Lecture notes** by slide topic.
5. **Readings.**
6. **Doctrine flowchart(s):** one per core doctrine applied to facts (section 5).
7. **Case notes:** citation and court; summary; facts; issues; held; principle; link to seminar or exam; check line; then, where supplied, the judgment and paragraphs or pages for reference.
8. **Comparison table** where authorities, tests or regimes are easily confused.
9. **Seminar questions with working answers** (General knowledge (verify) unless taken from class), problem questions in issue, rule, application, conclusion order.
10. **Critical point:** one line per doctrine: strength, weakness, or policy assumption.
11. **One-page exam sheet:** rules and tests, leading authorities, the flowchart in miniature, common traps.
12. **Spaced review:** which earlier weeks to revisit this week: Week N-1 (exam sheet), Week N-3 (flowcharts and case bank rows), Week N-7 (critical points). Skip rows that do not exist and reading weeks.

**C. Cross-week sections** (updated every week, never rebuilt): concept map; timeline (where history matters); case bank (topic, case, week, status, key facts, principle, why useful, and what it is not authority for); glossary (term, definition, source, first seen); critical evaluation; practice; gaps and things to verify.

Adapt headings to the module (essay-heavy modules lean on critical points and timelines; problem-question modules lean on flowcharts and practice) but keep the shape and the labels.

## 5. Visuals, cheap on tokens

- Default to Mermaid code blocks for flowcharts, concept maps and timelines, and Markdown tables for comparisons.
- Flowcharts follow the order of a problem-question answer; decision diamonds for tests; leaves name the leading authority; ten nodes or fewer.
- Concept map: `graph LR`, nodes tagged with their week, edges labelled; add to it, never redraw it.
- Timelines: Mermaid `timeline`, using only dates from the materials.
- Use a drawn figure only on request or if Mermaid does not render.
- Visuals carry only what the materials state. At most two new visuals per week, plus the concept-map update.

## 6. Weekly workflow

1. **Intake:** identify module and week; read only the parts of the guide needed.
2. **Check the brief:** apply section 2 first if anything looks like an assessment.
3. **List cases and statutes named;** ask for reports or extracts for any that matter and have none.
4. **Write the week** (section 4B), two to four sections per update, preserving the student's wording for pasted text.
5. **Update cross-week sections.**
6. **Flag conflicts and slips** in the section and in Gaps; never silently correct.
7. **Sync admin** only if it changed.
8. **Log** one line in the AI-use log.
9. **Close the loop** in chat: one line, the link, and what is still needed.

## 7. Token discipline

Read sections, not whole guides; edit in place; cross-reference by week instead of restating; Mermaid and tables over images; short chat replies.

## 8. Checks before finishing

- Every definition carries one of the two labels; no fact or pinpoint without a supplied source or the General knowledge (verify) label.
- The week has Builds on / leads to, an exam sheet and a spaced review table; the concept map and case bank include it.
- Nothing dropped; new content under the right week.
- Nothing written that could be submitted for assessment; AI-use log updated.

## 9. Module registry (template)

| Module | Code | Term | Teaching dates | Group / format | Assessment | Guide state |
| --- | --- | --- | --- | --- | --- | --- |
| [Module] | [Code] | [Term] | [Day, time, dates] | [Group, format] | [Format, date, weighting] | [Not started / Weeks 1-N] |

---

**Notice.** © 2026 Alexander Morales. All rights reserved. "law-study-guide" (public edition v1.0) is the intellectual property of Alexander Morales. Shared for personal, non-commercial use and reference only. No licence to copy, modify, redistribute, sublicense, sell or publish this work, in whole or in part, is granted without the author's prior written permission. This notice must not be removed. The skill is a study aid: it gives no legal advice, and users remain responsible for complying with their own institution's academic integrity and AI policies.
