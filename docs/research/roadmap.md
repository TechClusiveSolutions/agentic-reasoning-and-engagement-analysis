# AREA Program Roadmap

## Study Sequence

- **Study 1**: Instruction integrity baselines. CCQ and ITCR. Three task types. Isolated context.
  - Status: Design complete. Infrastructure build in progress.
- **Study 2**: Contextual judgment and ethical coherence. EDC, ADR, MAR. Forced failure and anomaly detection.
  - Status: Design complete. Awaiting Study 1 findings.
- **Study 3+**: Human-in-the-loop configurations addressing Research Questions 2 and 3. TBD based on Study 1 and 2 findings.
  - Status: Planned.

## Track Sequence

- **Track A**: Instruction structure (Study 1)
  - Dependency: None
- **Track B**: Personality type
  - Dependency: Study 1 baselines
- **Track C**: Communication modality
  - Dependency: Study 1 baselines; connects to Study 2 Scenario Family A
- **Track D**: Developmental capability gaps
  - Dependency: Study 1 baselines; connects to Study 2 Scenario Family B
- **Track E**: Cognitive function expression and compatibility
  - Dependency: Tracks A–D findings

## Phase Structure

- **Phase 0**: Local pilot. Single site. Local model. Isolated context. Study 1 Task Types 1–3. Establishes laboratory baseline.
- **Phase 1**: University anchor. API-hosted models. Expanded runs. First publishable findings. Dr. Badri Adhikari (UMSL) is primary target for first faculty conversation.
- **Phase 2**: Library deployment. Three parallel library sites. Real patrons. Validates laboratory findings in real-world context.

## Consortium Model and Participation Guide

The AREA program is structured as an open research consortium hosted by
Tech-Clusive Solutions LLC. Participating institutions contribute resources
appropriate to their capacity and gain access to the shared experimental
infrastructure, accumulated dataset, and collaborative network commensurate with
their contribution.

The consortium is designed to scale: Phase 0 is a single-PI pilot, Phase 1 adds
the first university partner, and Phase 2 expands to multiple sites running in
parallel. The participation model is the same at every scale — contribution tier
determines access level, not institutional type or size.

### Contribution Tiers

- **Core research team**
  - Contribution: Experimental design, methodology development, primary analysis
  - Access: Full program leadership, first authorship eligibility on primary publications
- **Technical implementation**
  - Contribution: Orchestration layer, platform engineering, logging infrastructure
  - Access: Full dataset access, co-authorship on methods and technical publications
- **Compute contributors**
  - Contribution: GPU and server resources (cloud credits, dedicated hardware, or both)
  - Access: Priority dataset access, co-authorship on publications that rely on contributed compute
- **Distributed evaluation network**
  - Contribution: Human scoring for subjective ITCR and CCQ items
  - Access: Full dataset access, inter-rater reliability publication credit
- **Replication partners**
  - Contribution: Predefined experimental subsets run at independent institutions
  - Access: Dataset access scoped to contributed experimental subset, replication publication credit

### What Participation Involves

**For university research partners (Phase 1 target)**

University partners contribute one or more of the following: graduate student
researcher time, faculty advisory capacity, compute access through existing cloud
research credits (NSF ACCESS, Google TPU Research Cloud, AWS Research Credits,
etc.), or replication capacity. In return, university partners gain co-investigator
status on the shared dataset, co-authorship on publications drawing on their
contribution, and access to the full accumulated AREA dataset for independent
analysis within the program's data governance terms.

A university partner's first engagement is typically a replication of Study 1 Task
Type 1 (Blackjack) under predefined conditions, using the shared infrastructure.
This serves as both a methodological validation and an onboarding exercise. Full
consortium access follows successful replication.

**For library and institutional deployment partners (Phase 2 target)**

Library and institutional partners host one deployment site running Task Types 2
and 3 (Library Patron Accessibility Request and Library Resource Accessibility
Onboarding) with real patrons and real resources rather than simulated inputs.
Participation requires: site coordinator designation, IRB or equivalent ethics
review, and integration of the AREA orchestration stack into the partner's
environment.

Partners receive: full access to findings from their site's data, co-authorship on
publications addressing real-world deployment findings, and a validated
accessibility evaluation and onboarding framework they can continue using after the
study period.

**For compute contributors**

Compute contributions can be structured as cloud credits, dedicated GPU access, or
on-premises hardware allocation. The minimum useful contribution at Phase 1 scale
is sufficient to run the local 7B model host plus orchestration layer for the
Study 1 run matrix (75 minimum runs). At Phase 2 scale, contributions that support
multi-site parallel execution or API-hosted model access are most valuable.

Compute contributors are credited as named contributors in all publications and
receive full dataset access. Contributions are acknowledged in the methods section
of all publications that used the contributed resources.

**For distributed evaluation network participants**

Some ITCR and CCQ scoring items require human judgment — particularly at low
instruction integrity levels where agent behavior is most ambiguous. The
distributed evaluation network consists of trained scorers who evaluate a
predefined subset of runs against the published scoring rubric.

Participation requires: completion of a calibration exercise establishing inter-
rater reliability above the threshold specified in the scoring protocol, agreement
to the data governance terms, and commitment to score a minimum batch size per
participation period. Network participants are credited as named contributors in
inter-rater reliability publications and receive access to the scored dataset.

### Data Governance

All consortium participants operate under a shared data governance agreement
covering: data ownership (Tech-Clusive Solutions LLC retains ownership of the
master dataset; partners receive licensed access to subsets commensurate with
their contribution), publication rights (all publications require PI approval and
acknowledgment of the AREA program), and confidentiality (participant institution
names and individual participant data from library deployments are not disclosed
without explicit consent).

The dataset is maintained as a versioned archive. Each study phase produces a
named dataset release. Partners who contributed to a phase receive perpetual
licensed access to that release.

### How to Express Interest

The AREA program is in Phase 0 (pilot infrastructure build). The first university
partner conversation is targeted for after pilot data is available. Institutions
and researchers interested in participating should contact the Principal
Investigator directly:

**Jad Wauthier** — jad@techclusivesolutions.com  
President & CTO, Tech-Clusive Solutions LLC  
On behalf of AREA Research Program

*AREA Research Program — Agentic Reasoning and Engagement Analysis*
*Jad Wauthier, Principal Investigator — on behalf of Tech-Clusive Solutions LLC*
*This document supersedes all previous versions of the AREA program overview.*

---

*AREA Research Program — Agentic Reasoning and Engagement Analysis*
*Jad Wauthier, Principal Investigator — on behalf of Tech-Clusive Solutions LLC*
