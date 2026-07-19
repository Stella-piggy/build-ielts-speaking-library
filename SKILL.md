---
name: build-ielts-speaking-library
description: Build, update, and use a personal IELTS Speaking material library from pasted or uploaded Part 1, Part 2, and Part 3 question banks. Use when a learner wants high-information interviews grounded in real experiences, reusable profile/story/viewpoint cards, question clustering and coverage mapping, on-demand 5.5-6 and 6.5-7 answer versions, or feedback on a spoken or written practice answer. Also use when continuing from an existing ielts-speaking-library.md file. Do not use for mass-producing generic model answers or inventing personal experiences.
---

# Build IELTS Speaking Library

Build a compact, reusable speaking library from the learner's confirmed facts and real language. Prioritize Part 2 story reuse in version 1; use Part 1 to build profile cards and Part 3 to build viewpoint cards.

## Load the right references

- Read [references/asset-schemas.md](references/asset-schemas.md) whenever creating, updating, importing, or exporting the library.
- Read [references/interview-and-mapping-rules.md](references/interview-and-mapping-rules.md) whenever parsing a question bank, planning interviews, resolving conflicts, clustering questions, or mapping cards.
- Read [references/answer-rubric.md](references/answer-rubric.md) whenever generating an answer or reviewing practice.
- Read [references/examples.md](references/examples.md) only when a concrete pattern is needed for an ambiguous or failure-prone case. Never treat its synthetic facts as the learner's facts.

## Start the session

Offer two concise entries:

1. 建立或更新个人素材库
2. 使用已有素材进行口语练习

Look for an attached, pasted, or workspace `ielts-speaking-library.md`. If the learner chooses practice but no library exists, explain that a confirmed library is required and start the build flow. If a library exists, import it, preserve its IDs, and ask only for information needed by the current task.

Accept Chinese, English, or mixed-language input. Reply in the learner's preferred language while keeping English answer content in English.

## Build or update the library

1. Accept a pasted or uploaded IELTS Speaking question bank. If no question bank is present, ask for it before planning interviews.
2. Extract the Part, exact original question, topic, response requirements, and needed material type for every item.
3. Put only exact duplicates and strict task-equivalent paraphrases in one duplicate group. Keep similar prompts with different actors, relationships, time frames, speech acts, or required facts in separate groups; preserve every original wording.
4. Cluster separate task groups by reusable content, not merely shared keywords. A shared cluster never makes two task groups duplicates. Let the number of clusters follow the data.
5. Show a compact parsing audit with exact/task-equivalent groups, similar-but-distinct pairs, clusters, and any unassigned question. Reconcile every unique task group before interviewing.
6. Compare cluster coverage with confirmed cards already in the library. Plan 6-8 interview modules that maximize uncovered coverage without bundling unrelated truth conditions. Show the plan briefly, then interview one module at a time. Ask exactly one high-information main question for the module and at most two precise follow-ups if essential information is missing.
7. After the module, present candidate personal facts and their proposed source. Ask the learner to confirm, correct, or reject them.
8. Write only explicitly confirmed facts into the library. Keep unconfirmed candidates outside the library. Resolve contradictions before updating any card.
9. Create or update profile, story, and viewpoint cards using the schemas. Split viewpoint cards when the central claim, actor, or question function differs, even when one answer supplies several positions. Render every field in schema order; use `未提供` for exhausted gaps instead of omitting a field. Record provenance on every card.
10. Map cards to every exact original question as `自然覆盖`, `调整后可用`, or `不建议使用`. Include the angle, required changes, and forced-link risk.
11. Output a question-to-card mind map, coverage counts, and missing material. Recommend a supplementary interview when no card fits; never force a story into a question.
12. Generate answers only after the learner selects a specific question. Never batch-generate the whole bank.

Follow all confirmation, deduplication, interview-budget, conflict, and mapping rules in `references/interview-and-mapping-rules.md`.

## Answer a selected question

Use only confirmed facts from the library plus facts the learner explicitly supplies for this answer. If the prompt needs a missing fact, ask for it or label it missing instead of guessing. Freeze a task-specific fact ledger before drafting: omit confirmed facts that do not help answer the selected prompt. Run a fact-difference check after drafting; Version B may reorganize or develop relevant confirmed facts but may not add an unstated ambition, cause, emotion, consequence, relationship, or example.

Generate both target versions and all nine required sections in `references/answer-rubric.md`. Make Version B better through development, cohesion, precise phrasing, flexible paraphrase, and controlled grammar variety—not word-for-word synonym substitution. Calibrate the spoken style from real samples and explicit learner feedback. Preserve useful personal and professional detail; when an answer feels too written, make targeted phrasing or sentence-level edits before shortening or rebuilding it. Apply the fact, spoken-rhythm, retrievability, and personal-voice checks before presenting it.

In section 5, compare the versions under the four IELTS Speaking criteria. For text-only input, discuss only observable organization, vocabulary, and grammar; explicitly state that live fluency and pronunciation cannot be scored from a script. Never infer hesitation, speech rate, rhythm, stress, intonation, linking, or intelligibility from text.

For Part 3, include a position, reason, and relevant example. A personal story may illustrate the argument but cannot replace it.

## Review practice

When the learner submits an English answer, apply the review sequence in `references/answer-rubric.md`: task response, logic, meaning-blocking language, repetition or stiff wording, minimal edit, then 6.5-7 spoken upgrade. Preserve the learner's successful structure and extract only 3-5 high-value expressions. Treat learner preference as calibration evidence; do not overcorrect a full answer when a few local changes are enough.

Do not comment on pronunciation from text or from automatic-transcript spelling. If the environment genuinely decodes real audio, give cautious feedback on clarity, stress, rhythm, intonation, and linking; state that it is practice guidance, not an official IELTS score.

After the learner confirms that a practice sample reflects their natural expression, update relevant cards and the language-style record. Never infer style from age, major, gender, personality labels, or stereotypes.

## Persist and hand off

After every confirmation, card update, selected-question answer, or practice review, update the complete master document defined in `references/asset-schemas.md`. Render all affected card fields and preserve every source question, mapping, coverage result, gap, mind map, and style record. Write or update `ielts-speaking-library.md` when file creation is supported; otherwise return the complete Markdown snapshot. Finish this checkpoint before moving to the next interview question.

Preserve exact source questions, stable IDs, confirmed provenance, and prior material unless the learner explicitly corrects or removes it. Never save unconfirmed facts in the snapshot.

Keep the output proportional: show the current question or changed cards first, then the complete reusable Markdown library. Do not add a website, external API, automated question-bank scraper, complex database, or unrelated files.
