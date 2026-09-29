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

- **MC-U01 · constraint / limit / threshold / ceiling** — constraint 是一般“约束”；limit 是允许的界限；threshold 是触发某行为的临界点，不一定是绝对上限；ceiling 强调最大允许值。例：The cleanup threshold is lower than the allocation ceiling. 关联：MC-V01、MC-V03、MC-V04。
- **MC-U02 · throughput / latency / capacity** — throughput 是单位时间处理多少；latency 是一次请求花多久；capacity 是最多能容纳或处理的量，具体含义必须说明。例：Increasing capacity does not necessarily reduce latency. 关联：MC-V12、MC-V13、MC-C19。
- **MC-U03 · transient / sustained / cumulative / aggregate** — transient 是短暂；sustained 是持续；cumulative 强调逐步累积；aggregate 强调多个部分的合计。例：A transient spike is different from sustained growth in aggregate usage. 关联：MC-V17–MC-V20。
- **MC-U04 · block / defer / reject** — block 通常表示等待；defer 是推迟处理；reject 是拒绝接受。不能把“暂时没完成”直接写成“被拒绝”。例：The request was deferred, not rejected. 关联：MC-V06、MC-V58、MC-P24。
- **MC-U05 · confirm / support / be consistent with / refute** — confirm 表示在明确范围内得到验证；support 提供支持；be consistent with 只表示相容；refute 要有反驳证据。没有证实不等于证伪。例：The result supports the hypothesis, but further testing is needed. 关联：MC-V31–MC-V33、MC-C34、MC-P12。
- **MC-U06 · observe / infer / predict** — observe 是观察到；infer 是根据证据推断；predict 是事先预测。例：We observed a timeout, inferred that the task might be blocked, and predicted that freeing capacity would let it resume. 关联：MC-V36、MC-P18。
- **MC-U07 · evidence / finding / result** — evidence 通常不可数：some evidence、a piece of evidence，不写 an evidence；finding 和 result 可数。例：These findings provide evidence for a narrower claim. 关联：MC-V30、MC-V35、MC-P19。
- **MC-U08 · fall back / fallback / fall through** — fall back 是动词短语；fallback 是名词或定语；fall through 在代码语境中指继续进入后面的路径，未必意味着主动选择备用方案。例：The request falls back to a slower method through the fallback path. 关联：MC-V53、MC-C28、MC-C29。
- **MC-U09 · on its own / in its own / by itself** — 表达“单凭它”用 on its own 或 by itself；in its own 后通常还需名词。例：A counter on its own does not prove that the entire system is bounded. 关联：MC-C35、MC-P13。
- **MC-U10 · attribute X to Y / result in / result from** — attribute the failure to overload 表示“把失败归因于过载”；overload results in failure 表示“过载导致失败”；failure results from overload 表示“失败源于过载”。例：Do not attribute every delay to the same cause. 关联：MC-V37、MC-C33。
- **MC-U11 · while / whereas / unless / until** — while 可表示同时或对比；whereas 明确对比；unless 是除非；until 是直到。例：The writer waits until capacity is released, unless a separate path allows it to proceed. 关联：MC-P03、MC-P17。
- **MC-U12 · bound / bounded / boundary** — bound 作动词表示限制，过去式和过去分词为 bounded；a bound 是数学或技术上的界限；boundary 是边界。不要把 bound 的过去式误写为 bound（后者也可能是 bind 的过去式）。例：The setting bounds pool growth, but it does not bound total process memory. 关联：MC-V21、MC-V22、MC-P22。
