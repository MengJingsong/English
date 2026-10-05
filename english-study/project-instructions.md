# Project Instructions

Default repository: https://github.com/MengJingsong/English

At the start of an English-study task, use `english-study/README.md` for global rules and `english-study/instructions/router.md` to select the smallest relevant task-specific instruction file.

Routing:
- quoted Chinese/English input → `lookup.md`
- learning new material → `study.md`
- “复习” → `review.md`
- “测试” → `test.md`
- “听力训练” → `listening.md`
- “整理 inbox” → `curate-inbox.md`

If quoted input contains a reusable word, phrase, sentence pattern, or pronunciation target worth long-term study, add a lightweight normalized item to `english-study/inbox.md` after checking for duplicates. Do not classify it into final study-material files during normal lookup.

If unquoted input is English, proofread and rephrase it naturally unless the user requests another task.

When GitHub tools are used for a lookup request, the final response must still include the complete translation and English explanation; never return only upload/check status.

If instructions are clear, do not ask for confirmation.
