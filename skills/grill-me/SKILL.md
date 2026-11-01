---
name: grill-me
description: Use when the user says "grill me", "interrogate me", "ask me questions first", invokes /grill-me, or hands over a significant vague task where wrong assumptions are expensive - new build, new offer, new page, new client, big change.
---

# Grill Me

## Overview

Interrogation BEFORE any work. Surface what the user knows but has not said. No drafting, building, or file edits until the user confirms a brief.

A grill is a loop, not a questionnaire.

## The contract: four stages, in order

1. **Recon.** Read what the task touches: files, docs, prior decisions. Never ask what the workspace already answers.
2. **Rounds.** 3-5 questions per round, most load-bearing first. Number them and give each a suggested default so the user can answer fast ("2: default is fine"); use a structured question tool if you have one. Pin vague answers ("make it pop") to something observable. Repeat until a round surfaces no new load-bearing unknown; typically 2-4 rounds. Seed questions: `references/question-bank.md`.
3. **Brief.** Play back: Goal (one sentence), Non-goals, Decisions, Assumptions (defaults accepted), Open items (parked, non-blocking), Plan (first steps), Done means (observable).
4. **Gate.** Ask "anything wrong or missing?" Begin work only after explicit confirmation. Partial answers never justify a "first draft".

Record answers with `references/answers-template.md`; append to the project's progress log if one exists.

## Territory (skip what recon answered)

| Area | Question behind the question |
|---|---|
| Outcome | What does done look like? The one action or metric? |
| Audience | Who exactly is it for? |
| Scope | What is explicitly out? |
| Constraints | Budget, deadline, platforms, dependencies |
| Prior art | Which existing pieces and decisions apply? |
| Risks | What breaks, embarrasses, or costs money if wrong? |
| Approval | What must the user sign off before it ships? |

## Red flags

- Starting to build with an unasked expensive assumption
- Asking 15 questions at once (8+ is already too many)
- Questions with no default offered
- Asking what the repo already answers
- Going from answers to work with no played-back brief
- Calling one round enough

## Common mistakes

| Mistake | Fix |
|---|---|
| Open question, no default | Offer a recommended default |
| Accepting "whatever's standard" | Ask which standard, name an example |
| Treating a partial answer as a green light | Park it as an open item, keep going |
| Brief never played back | Always run the gate |

## When not to use

Small, well-specified tasks (typo, one copy tweak, work with a confirmed spec). Confirm the single ambiguous point and proceed.
