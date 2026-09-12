---
schema: paper-monitor/paper/v1
paper_id: 6601
record_type: PAPER
bibliography:
  title: '[PDF] CL4SE: Benchmarking Context Learning on Software Engineering'
  authors: Haichuan Hu, Quanjun Zhang, Ye Shang, Guoqing Xie, Chunrong Fang, Zhenyu Chen, Liang Xiao
  abstract: Context engineering has emerged as a pivotal paradigm for unlocking the potential of Large Language Models (LLMs)
    in Software Engineering (SE) tasks, enabling performance gains at test time without model fine-tuning. Despite its success,
    existing research lacks a systematic taxonomy of SE-specific context types and a dedicated benchmark to quantify the heterogeneous
    effects of different contexts across core SE workflows. To address this gap, we propose CL4SE (Context Learning for Software
    Engineering), a comprehensive benchmark featuring a fine-grained taxonomy of four SE-oriented context types (interpretable
    examples, project-specific context, procedural decision-making context, and positive & negative context), each mapped
    to a representative task (code generation, code summarization, code review, and patch correctness assessment). We construct
    high-quality datasets comprising over 13,000 samples from more than 30 open-source projects and evaluate five mainstream
    LLMs across nine metrics. Extensive experiments demonstrate that context learning yields an average performance improvement
    of 24.7% across all tasks. Specifically, procedural context boosts code review performance by up to 33% (Qwen3-Max), mixed
    positive-negative context improves patch assessment by 30% (DeepSeek-V3), project-specific context increases code summarization
    BLEU by 14.78% (GPT-Oss-120B), and interpretable examples enhance code generation PASS@1 by 5.72% (DeepSeek-V3). CL4SE
    establishes the first standardized evaluation framework for SE context learning, provides actionable empirical insights
    into task-specific context design, and releases a large-scale dataset to facilitate reproducible research in this domain.
  publisher: arXiv.org.
  published_on: '2026-02-26'
  doi: null
links:
  source: http://arxiv.org/abs/2602.23047v3
  open_access: https://arxiv.org/abs/2602.23047v3
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

