# AREA Terminology

## Hierarchy

```
Study → Scenario → Task → Action → Run
```

- **Study**: An experiment. Defines the overall types of data collected, the means of collection, and the way the data will be analyzed. Contains a specified number of scenarios.
- **Scenario**: The environmental and contextual container for a set of tasks. Builds a controlled framework describing behavioral and operational boundaries. Example: "You are in a smoky bar. The music is loud. There are lots of drunk people all around you." The scenario is the situation, not the task. The same tasks can run in different scenarios to test whether findings generalize across contexts.
- **Task**: A defined goal-directed unit of work within a scenario. "Play a hand of blackjack." "Make an accessible version of this document." Tasks have a defined objective, a starting state, and a terminal state. Multiple tasks form a scenario.
- **Action**: The standard unit of work for an agent. A discrete step taken to complete a task. "Retrieve an index of available resources via API." "Ask Agent 2 for the patron's email address." Actions are what get logged in the event stream. Multiple actions form a task.
- **Run**: An execution variant of a scenario. The controlled mechanism by which independent conditions are systematically varied. "Run Scenario 2 with Instruction Integrity Level 3, Patron Profile B, Agent Configuration 1." A run is defined by its full parameter set.
- **Trial**: A set of runs sharing the same parameter configuration. Five runs at the same instruction level and task type constitute a trial. Trial-level statistics aggregate across runs.

## Core Terms

- **Coordination**: Two or more agents working together to solve a problem or accomplish a task.
- **Instructional integrity**: The complexity and richness of an instruction, involving: completeness, correctness, order, diction, formality, and rigidity.
- **Entity**: An institution, organization, or individual running a study.
- **Site**: A particular location in which a study is being run. The same study can run at multiple sites simultaneously. All database tables include a `site_id` field to support multi-site collection without schema changes.
- **Directive conflict**: Two or more directives in an instruction that cannot both be satisfied simultaneously under at least some operating conditions.
- **Manufactured coherency**: An apparent resolution mechanism that disguises a real directive conflict. More dangerous than an obvious contradiction because it may cause an agent to execute an incorrect action while believing it has correctly followed the instruction.
- **Authorization ambiguity**: A scope of permitted action that is undefined in a way that could lead an agent to exceed its actual authority.
- **Metacognitive activation**: An agent's recognition that a situation requires knowledge or capabilities it does not currently possess, followed by appropriate action to acquire what is needed.
- **Emergent detection**: Anomaly detection achieved by a coordinated agent group that no individual agent in the group could achieve alone. Calculated as Group ADR minus mean individual agent ADR.

## Metric Abbreviations

- **CCQ** — Collective Coordination Quality**: Group-level coordination metric, 0.0–1.0 scale across six dimensions. Study 1 primary metric.
- **ITCR** — Individual Task Completion Rate**: Per-agent action completion metric, 0.0–1.0 scale. Study 1 primary metric.
- **EDC** — Ethical Decision Coherence**: Group ethical decision quality in forced failure conditions. Study 2 primary metric.
- **ADR** — Anomaly Detection Rate**: Proportion of anomalies correctly detected and responded to. Study 2 primary metric.
- **MAR** — Metacognitive Activation Rate**: Proportion of knowledge-gap situations correctly recognized and addressed. Study 2 primary metric.

---


---

*AREA Research Program — Agentic Reasoning and Engagement Analysis*
*Jad Wauthier, Principal Investigator — on behalf of Tech-Clusive Solutions LLC*
