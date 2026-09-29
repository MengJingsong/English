<!--
FORMAT RULES:
- One vocabulary/phrase/pattern/sentence item per line.
- Every study item starts with "- ".
- Examples are newly written teaching examples, not quotations or new experimental results.
- Source links identify the wording or idea from which an item was extracted or adapted.
- Existing corpus overlaps are intentional usage expansions, not evidence of mastery.
Source: MengJingsong/Misconfiguration @ 7348bdb964b315ea2e2963e3f1523d17e080897e
Prepared: 2026-09-29
-->

<!-- Practice is ungraded. Do not update english-study/mastery.md or session-log.md merely because this file exists. For a listening-training request, return only the selected English passages, without IDs, bullets, headings, translations, source links, or commentary. Answer suggestions live in answers.md so target expressions can remain hidden during recall. -->
# Listening passages
- **MC-L01 · A growing backlog** — The service looks healthy when traffic is light, but the picture changes under sustained load. Requests arrive faster than the workers can process them, and a backlog begins to grow. Adding workers might improve throughput, but we first need to understand the source of contention. If several workers are waiting for the same disk, increasing the worker count may have little effect. Before changing the configuration, let's measure the arrival rate, processing rate, and latency.
- **MC-L02 · What the graph tells us** — The new graph is consistent with our hypothesis, but it does not confirm it on its own. Memory usage stayed below the expected ceiling, yet the workload may never have reached the limit. To make the comparison meaningful, we should hold the workload fixed while varying the setting. We also need direct evidence that the capacity check affected the request. Without that signal, we cannot tell whether the limit worked or the experiment simply failed to put enough pressure on the system.
- **MC-L03 · A careful handoff** — I have traced the unexpected value back to its source and checked the relevant references. The analysis is complete, but what remains is to write it up. Please keep the summary self-contained and record the provenance of each result. The older procedure has been superseded, so use the revised version as the baseline. If you run into a gap, note it explicitly. That will help the next person pick up the work without repeating the investigation from scratch.
- **MC-L04 · A limit with a narrower scope** — The setting places a ceiling on one pool, but the caller has a fallback path. Once the pool is full, a request may obtain memory elsewhere. This means the pool can remain bounded while aggregate usage continues to rise. A lower pool limit therefore does not necessarily produce lower total usage. We need to distinguish the pool's own allocation from the memory used outside it, and we should state that distinction clearly when reporting the result.

# Active recall
- **MC-E01 · 中文转英文** — “我们应该保持工作负载不变，同时改变内存限制。”先口头回答，再写出一句自然英文，不看词表。
- **MC-E02 · 中文转英文** — “这一结果与我们的假设一致，但单凭它还不能证实该假设。”使用一个完整句子，并保留证据强度。
- **MC-E03 · 中文转英文** — “消费者跟不上新增工作的速度，因此积压不断增加。”避免逐字翻译“跟上速度”。
- **MC-E04 · 中文转英文** — “只有核对完所有引用，这次审查才算完成。”使用带否定的时间句式。
- **MC-E05 · 改错并解释** — “These evidences prove the service is always safe.” 已知事实只有“一次单元测试通过”；修正可数性和过度推断两个问题。
- **MC-E06 · 改错并解释** — “We attribute the failure for the new setting and will fallback to the old one.” 修正介词和动词短语写法。
- **MC-E07 · 情境表达** — 请求暂时停止，释放容量后继续完成。用一句话准确说明发生了什么；不要把等待写成永久拒绝。
- **MC-E08 · 情境表达** — 代码中的某个限制只约束一个组件。用两句英文说明为什么整个进程的总用量仍可能增长。
- **MC-E09 · 听后复述** — 听 MC-L02 两遍后，不看原文，用 30–45 秒说明“图表为什么不足以证实假设、还缺什么证据”。先自由表达，再检查是否保留原文的证据强度。
- **MC-E10 · 口语汇报** — 用 60 秒向同事交接一项未完成的调查：已完成什么、剩下什么、一个限制和下一步。先不看 MC-L03，也不展示目标短语。
- **MC-E11 · 写作** — 写一段 100–130 词的实验摘要：给定事实为“一个小规模测试通过；总内存未测量；尚无集群测试”。明确区分观察、推断、未测试的范围和下一步；不要补造实验数据。
- **MC-E12 · 延迟迁移练习** — 隔 2–3 天，用 5–6 句英文解释一个非技术场景：预算上限、积压的邮件或团队交接。先不展示目标词；回答后再检查能否自然使用本模块中的表达。
