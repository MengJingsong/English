# English Study

This folder stores learning state, testing history, and the rules ChatGPT should use when helping with this repository.

## Repository structure

- `/study-materials/` is the complete study corpus. Unless the user explicitly asks otherwise, vocabulary, phrases, expressions, patterns, and sentences to teach/test should come from that folder.
- `/english-study/` stores learning state and study-system metadata. It is not itself part of the study corpus.
- The repository root `README.md` is not study material.

## Goal

The goal is active mastery, not recognition alone. Training should develop:
- listening: recognize items in natural, relatively fast spoken English;
- speaking: recall and use items naturally without being given the target expression;
- writing: use items accurately and idiomatically;
- comprehension: understand meaning, nuance, register, and common contexts.

## Mastery scale

Use a 0–5 scale for each item:
- 0 = unfamiliar
- 1 = recognized but not usable
- 2 = understood in context
- 3 = usable with prompting
- 4 = usable spontaneously in new contexts
- 5 = retained and spontaneous across listening/speaking/writing after delayed review

Do not mark an item mastered from one immediate correct answer. Delayed, unprompted recall in a new context is stronger evidence.

## Testing principles

Prefer active recall over recognition. Progress from meaning/recognition to contextual discrimination, translation or completion, unprompted production, listening recognition, and integrated situational use.

For mature items, hide the target word/phrase and test whether the learner independently retrieves it. Re-test items after delays. Give extra weight to unprompted correct use and to successful delayed review.

Track skill-specific weaknesses when useful: listening, speaking, writing, and comprehension.

## Review selection

When choosing what to review, prioritize:
1. due/overdue items;
2. recently failed or weak items;
3. low-mastery items;
4. items not tested for a long time;
5. a smaller sample of mastered items for retention checks.

## Listening-training rule

When the user says “听力训练”, output only the English passage(s) intended to be heard. Do not add headings, explanations, translations, instructions, or commentary, because all extra text may be read aloud. Base passages primarily on `/study-materials/` and use natural, relatively fast conversational English.

## State files

- `mastery.md`: current per-item learning state. This is the primary state file.
- `session-log.md`: concise record of meaningful tests/reviews and notable errors or improvements.

Update state after meaningful testing. Avoid bloating the log with every trivial interaction.

## Default workflow for ChatGPT

At the beginning of a study/review session, read this README and the relevant study materials plus `mastery.md`. Select exercises based on current mastery rather than randomly. After testing, update mastery conservatively and add a concise session-log entry when useful.
