# Interview and Mapping Rules

## Contents

1. Parse and normalize the question bank
2. Cluster for reusable material
3. Plan 6-8 interview modules
4. Run and confirm interviews
5. Handle short, conflicting, or missing information
6. Map cards without forced linking
7. Report coverage and gaps

## 1. Parse and normalize the question bank

For every original item, extract:

- Part number
- exact wording and cue-card bullets
- topic
- answer obligations
- material type needed

Do not silently repair or paraphrase source questions. When a line is ambiguous, preserve it and mark the parsing uncertainty.

Deduplicate in two layers:

1. Exact duplicate: identical task after whitespace and numbering normalization.
2. Task-equivalent paraphrase: the same Part, question function, central target, actor or relationship, time or polarity constraints, and interchangeable answer obligations, even if wording differs.

Use this counterfactual test: if a complete answer to prompt A could still fail one explicit requirement of prompt B, keep them in separate duplicate groups.

Keep separate groups when similar wording changes any required truth condition. Examples include:

- `encouraged you to achieve a goal` versus `helped you achieve something`
- `a useful skill you learned` versus `a skill someone taught you`
- `a place you enjoy visiting` versus `a place affected by pollution`
- `should schools teach practical skills` versus `should parents teach practical skills`
- `why people give up` versus `should an institution teach`

Task groups and material clusters are different layers. Similar-but-distinct groups may share a cluster, interview, or card only when the confirmed facts satisfy each group independently. Before interviewing, show a compact audit of exact/task-equivalent groups, similar-but-distinct pairs, cluster membership, and any parsing uncertainty.

## 2. Cluster for reusable material

Cluster by the kind of confirmed material that could answer the prompts naturally. A story about learning photography may connect a skill, a difficult achievement, a helpful person, and a memorable place; a keyword-only `hobby` cluster would miss those links.

Do not predetermine the cluster count. Name each cluster with a concrete reuse anchor. Retain links from every cluster back to exact original questions.

Do not cluster solely because prompts share a noun. `an enjoyable place` and `a polluted place` require different truth conditions and should default to separate clusters or subclusters unless confirmed evidence already shows one real place naturally satisfies both.

## 3. Plan 6-8 interview modules

Choose 6-8 modules after reviewing both the question bank and existing confirmed cards. Rank candidates using:

- breadth of natural question coverage
- value for Part 2 story arcs
- current evidence gaps
- likelihood that one real episode contains specific detail and reflection
- balance across profile, story, and viewpoint needs

Favor modules such as a formative person, a challenge or achievement, a meaningful place, a useful object or technology, a leisure habit, a change or decision, and a social issue only when the bank supports them. These are examples, not a fixed taxonomy.

Show the plan as a compact table: module, target clusters, intended card types, known facts, missing facts. Then ask only the first module's question.

Before asking it, reconcile coverage: every unique task group must be assigned to at least one module or explicitly marked `deferred/missing`. Do not omit a group to stay within 6-8 modules; combine groups only when one coherent fact set or policy frame can answer them without asking several independent main questions.

For Part 3, a single module may gather several related positions, but keep each central claim and actor visible in the plan. Do not hide a causal `why` question inside an institutional `should` topic.

## 4. Run and confirm interviews

Ask one high-information main question per module. It may contain a short set of prompts inside one request, for example:

> 请回想一次你真实经历过、最后结果对你有影响的挑战，按你最自然的方式讲讲当时的时间地点、相关人物、你想做到什么、最难的地方、你采取的行动、结果和感受；可以用中文、英文或混合回答。

Do not ask multiple unrelated main questions in one turn. Before each module, check confirmed cards and prior answers; do not ask again for facts already confirmed. Ask only for uncovered requirements.

Use at most two follow-ups, and only to obtain information essential to a useful card or resolve ambiguity. For a short reply, rank missing obligations and ask the highest-yield causally connected gap. Make each follow-up answerable in one or two sentences; do not recite every missing schema field or bundle unrelated `where`, `why`, `result`, and `feeling` questions.

After the main answer and any follow-ups, show a candidate-fact block before writing:

```markdown
### 待确认事实（尚未写入素材库）
- ...
- ...
来源建议：用户本轮原话/澄清

请确认、修改或删除以上事实。
```

Require an explicit confirmation such as `确认`, `这些都对`, or a corrected list. Treat silence, a topic change, or an ambiguous reply as not confirmed.

Candidate facts must be entailed by the learner's words. Do not silently turn an action into a goal, a helper into an encourager, a visited place into a liked place, or an example into a general belief. Put any useful interpretation in a separate `待确认解释` subsection and label it as an inference, not a fact.

For viewpoint evidence, distinguish a concrete example from a mechanism or recommendation. `Schools could teach first aid` is a proposed measure, not a real example; `my university ran a first-aid workshop` is a concrete example. If the learner gives only a stance and reasons, use a focused follow-up for one real case or mark `现实例子` as `未提供`.

After confirmation, write the card, show what changed, and proceed to the next module only when appropriate. A profile card may combine closely related preferences and changes; a story card must describe one coherent event; a viewpoint card must contain one central claim or decision target. Split viewpoint cards when the actor (`schools` versus `parents`) or question function (`why` versus `should/how`) changes, even if one high-density interview supplied all facts.

## 5. Handle difficult evidence

### Answer is too short

First identify the single highest-value gap. Ask one focused follow-up. If still insufficient, ask at most one final focused follow-up. Then record only confirmed supplied details and mark the remaining field `未提供`; do not keep interrogating or fill it yourself.

### Facts conflict

Do not overwrite either version. Show the conflict neutrally and ask whether:

- one version is incorrect,
- both are true in different periods or contexts, or
- the learner wants to withdraw one statement.

Update or split cards only after confirmation. Never reinterpret a contradiction as a stylistic detail.

### No suitable material

Mark the mapping `不建议使用`, state the missing central requirement, and propose one focused supplementary interview. Do not change a person's identity, location, chronology, outcome, or emotion merely to improve coverage.

### Learner does not want to answer

Respect the skip. Mark the gap without guessing and re-optimize later modules around other real material.

## 6. Map cards without forced linking

Evaluate each exact original question against confirmed facts using this order:

1. Does the card satisfy the central noun or event requested?
2. Does it satisfy required relationship, time, change, problem, or outcome constraints?
3. Can the learner answer directly without a long explanation of why the material counts?
4. Can emphasis change while all facts remain true?
5. Would using it sound repetitive, implausible, or evasive?

Assign:

- `自然覆盖` when 1-3 are clearly yes and only ordinary detail selection is needed.
- `调整后可用` when the core is true but the angle or emphasis must change; name the exact adjustment.
- `不建议使用` when a central requirement is missing or the bridge would feel forced; name the risk.

Part 1 mappings normally draw on profile cards. Part 2 mappings normally draw on story cards. Part 3 mappings require a viewpoint card with position, reason, and example; a story can support but cannot substitute for the argument.

For Part 3, assign `自然覆盖` only when position, reason, and a concrete confirmed example are available. Assign `调整后可用` when a separate confirmed card can provide that example. Without any confirmed example, assign `不建议使用` and schedule a focused supplementary interview.

## 7. Report coverage and gaps

Produce:

- a card-to-question Mermaid mind map or indented tree
- counts for `自然覆盖`, `调整后可用`, and `不建议使用`
- uncovered central requirements
- the smallest set of supplementary interview topics likely to close important gaps

Do not claim that duplicate prompts increase the diversity of coverage. Mention both raw-question coverage and unique duplicate-group coverage when the distinction matters.
