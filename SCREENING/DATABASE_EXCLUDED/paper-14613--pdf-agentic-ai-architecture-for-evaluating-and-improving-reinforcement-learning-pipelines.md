---
schema: paper-monitor/paper/v1
paper_id: 14613
record_type: PAPER
bibliography:
  title: '[PDF] Agentic AI Architecture for Evaluating and Improving Reinforcement Learning Pipelines'
  authors: Evangelos Ntentos, Uwe Zdun
  abstract: Reinforcement Learning (RL) systems are gaining traction in application areas such as robotic systems, self-driving
    vehicles, and automated industrial operations.In these safety-critical domains, lifecycle management practices – including
    model versioning, registry integration, automated evaluation, retraining triggers, and staged deployments – are just as
    important as algorithmic performance in ensuring reliability and reproducibility. However, these practices are often scattered
    across source code, configuration files, CI/CD workflows, and deployment manifests, making it difficult to automate detection
    and correction. This paper introduces an Agentic AI architecture that utilizes multiple specialized LLM-based agents to
    evaluate RL pipelines against a curated catalog of 15 architectural best practices. The agents are specialized (e.g.,
    file selection, detection, fix suggestion, code generation), and an orchestrated pipeline with automated validation gates
    combines practice detection and LLM reasoning to identify both explicit and implicit practice gaps and suggest, or where
    appropriate, even apply fixes. We validate the approach in a large-scale industrial cyber-physical production case study
    and in five open-source RL repositories with diverse architectures, demonstrating the scalable detection of missing practices
    and the generation of actionable fixes. The system achieved an overall detection F1-score of 0.80 and a mean generation-quality
    score of 2.40, indicating that it reliably identifies missing practices and produces functionally valid code artifacts.
  publisher: Proceedings 2026 IEEE ACM 5th International Conference on AI Engineering Software Engineering for AI Cain 2026.
  published_on: '2026-04-12'
  doi: 10.1145/3793653.3793759
links:
  source: https://doi.org/10.1145/3793653.3793759
  open_access: https://doi.org/10.1145/3793653.3793759
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-12T04:09:22.005164Z'
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

