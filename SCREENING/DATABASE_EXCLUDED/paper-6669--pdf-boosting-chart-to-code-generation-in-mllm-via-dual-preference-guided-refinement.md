---
schema: paper-monitor/paper/v1
paper_id: 6669
record_type: PAPER
bibliography:
  title: '[PDF] Boosting Chart-to-Code Generation in MLLM via Dual Preference-Guided Refinement'
  authors: Zhihan Zhang, Yixin Cao, Lizi Liao
  abstract: 'Translating chart images into executable plotting scripts-referred to as the chart-to-code generation task-requires
    Multimodal Large Language Models (MLLMs) to perform fine-grained visual parsing, precise code synthesis, and robust cross-modal
    reasoning. However, this task is inherently under-constrained: multiple valid code implementations can produce the same
    visual chart, and evaluation must consider both code correctness and visual fidelity across diverse dimensions. This makes
    it difficult to learn accurate and generalizable mappings through standard supervised fine-tuning. To address these challenges,
    we propose a dual preference-guided refinement framework that combines a feedback-driven, dual-modality reward mechanism
    with iterative preference learning. Our approach introduces a structured variant generation strategy and a visual reward
    model to efficiently produce high-quality, aspect-aware preference pairs-making preference collection scalable and supervision
    more targeted. These preferences are used in an offline reinforcement learning setup to optimize the model toward multi-dimensional
    fidelity. Experimental results show that our framework significantly enhances the performance of general-purpose open-source
    MLLMs, enabling them to generate high-quality plotting code that rivals specialized chart-centric models and even some
    proprietary systems. The code and datasets are publicly available at https://github.com/Zhihan72/Chart2Code.'
  publisher: Mm 2025 Proceedings of the 33rd ACM International Conference on Multimedia Co Located with mm 2025.
  published_on: '2025-10-25'
  doi: 10.1145/3746027.3755596
links:
  source: https://doi.org/10.1145/3746027.3755596
  open_access: https://doi.org/10.1145/3746027.3755596
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

