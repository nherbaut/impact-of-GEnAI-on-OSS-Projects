---
schema: paper-monitor/paper/v1
paper_id: 6563
record_type: PAPER
bibliography:
  title: '[PDF] A comparative analysis of the role of Large Language Models and Low-Rank Adaptation in Automated Program Repair'
  authors: Celia Patricio, Pablo Zubasti, Antonio Berlanga, Miguel Á. Patricio
  abstract: 'Context: Large Language Models (LLMs) have recently reframed Automated Program Repair (APR) as a conditional
    code-generation task. However, practical adoption faces challenges such as overfitting to incomplete test suites, high
    token/computational costs, and inconsistent evaluation methodologies. Objectives: This paper presents a unified framework
    to analyze how orchestration strategies (single-shot vs. iterative feedback) and parameter-efficient fine-tuning via Low-Rank
    Adaptation (LoRA) influence repair effectiveness, efficiency, and patch quality in single-function Java defects. Methods:
    We implement and compare four repair pipelines—linear and iterative variants, with and without LoRA—across both open-source
    and proprietary LLMs using standardized benchmarks (Defects4J and HumanEval-Java). The design isolates the impact of iterative
    orchestration from that of LoRA-based specialization under a consistent evaluation protocol. Results: Our findings show
    that iterative prompting markedly increases the number of plausible and correct patches while controlling token and time
    costs. When combined with iterative feedback, LoRA further improves semantic correctness with minimal overhead. Conclusion:
    This study is the first to systematically disentangle the effects of repair orchestration and lightweight specialization
    using LoRA within a common framework. We provide empirical evidence that open-source models, enhanced by LoRA and feedback,
    can match the performance of proprietary models while offering shorter, cheaper patches. By experimentally disentangling
    orchestration from specialization within a unified protocol, the study clarifies their respective contributions to effectiveness
    and efficiency in LLM-based APR.'
  publisher: Information and Software Technology.
  published_on: '2026-06-20'
  doi: 10.1016/j.infsof.2026.108238
links:
  source: https://doi.org/10.1016/j.infsof.2026.108238
  open_access: https://doi.org/10.1016/j.infsof.2026.108238
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

