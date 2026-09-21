---
schema: paper-monitor/paper/v1
paper_id: 6573
record_type: PAPER
bibliography:
  title: '[PDF] SpecBench: Evaluating Specification-Level Reasoning for Software Engineering LLM Agents'
  authors: Grant Hamblin, Kevin Song, Zhanda Zhu, Anand Jayarajan, Sihang Liu, Nandita Vijaykumar, Gennady Pekhimenko
  abstract: 'Software engineering (SWE) agents are transitioning from code generation to full software development lifecycle
    automation. A critical phase in this lifecycle is specification design: transforming initial proposals into carefully
    considered requirements through expert review. Existing benchmarks such as SWE-Bench are implementation-focused by measuring
    the agent''s ability to generate code given fixed, precise design requirements. This formulation assumes specifications
    are correct and complete. In real-world complex and critical software systems, initial specifications are often incomplete
    and flawed, requiring extensive expert reviews and revisions before being accepted for implementation. To fill this gap,
    we introduce SpecBench to evaluate specification-level reasoning: the ability to generate complete, unambiguous, consistent,
    and correct system specifications. SpecBench tasks are derived from the Request for Comments (RFC) process used by mature
    open-source projects. For each task, an agent is given an initial design proposal, the project codebase, and all past
    project RFC discussions. The agent is tasked with identifying specification deficiencies: omissions, ambiguities, inconsistencies,
    or incorrect assumptions in the initial proposal. We evaluate predictions against critiques raised by expert maintainers
    during historical RFC reviews. SpecBench contains tasks from 5 diverse repositories: Kubernetes, React, Rust, TVM, and
    vLLM. We evaluate state-of-the-art SWE agents on SpecBench, analyzing their capacity to reason about system design without
    execution feedback. The best performing agent, GPT-5.4, achieves 44.4% accuracy.'
  publisher: arXiv.org.
  published_on: '2026-05-28'
  doi: null
links:
  source: http://arxiv.org/abs/2605.30314v1
  open_access: https://arxiv.org/abs/2605.30314v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-06-30T13:29:23.865282Z'
workflow:
  state:
    id: SCREENING/DATABASE_EXCLUDED
    label: Database excluded at screening
    prisma_bucket: DATABASE_SCREENING_EXCLUDED
  tags:
  - arxiv
  eligibility:
    exclusion: null
    inclusion:
      criteria: [
        ]
files:
  pdf:
    available: false
    name: null
    original_name: null
---

