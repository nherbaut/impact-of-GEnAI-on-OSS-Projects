---
schema: paper-monitor/paper/v1
paper_id: 6797
record_type: PAPER
bibliography:
  title: A Pair Programming Framework for Code Generation via Multi-Plan Exploration and Feedback-Driven Refinement
  authors: Huan Zhang, Wei Cheng, Yuhan Wu, Wei Hu
  abstract: Large language models (LLMs) have achieved impressive performance on code generation. Although prior studies enhanced
    LLMs with prompting techniques and code refinement, they still struggle with complex programming problems due to rigid
    solution plans. In this paper, we draw on pair programming practices to propose PairCoder, a novel LLM-based framework
    for code generation. PairCoder incorporates two collaborative LLM agents, namely a Navigator agent for high-level planning
    and a Driver agent for specific implementation. The Navigator is responsible for proposing promising solution plans, selecting
    the current optimal plan, and directing the next iteration round based on execution feedback. The Driver follows the guidance
    of Navigator to undertake initial code generation, code testing, and refinement. This interleaved and iterative workflow
    involves multi-plan exploration and feedback-based refinement, which mimics the collaboration of pair programmers. We
    evaluate PairCoder with both open-source and closed-source LLMs on various code generation benchmarks. Extensive experimental
    results demonstrate the superior accuracy of PairCoder, achieving relative pass@1 improvements of 12.00%--162.43% compared
    to prompting LLMs directly.
  publisher: Proceedings 2024 39th ACM IEEE International Conference on Automated Software Engineering Ase 2024
  published_on: '2024-10-18'
  doi: 10.1145/3691620.3695506
links:
  source: https://doi.org/10.1145/3691620.3695506
  open_access: null
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
  tags: [
    ]
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

