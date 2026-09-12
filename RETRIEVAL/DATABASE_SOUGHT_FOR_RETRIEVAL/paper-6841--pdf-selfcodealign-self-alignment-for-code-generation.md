---
schema: paper-monitor/paper/v1
paper_id: 6841
record_type: PAPER
bibliography:
  title: '[PDF] SelfCodeAlign: Self-Alignment for Code Generation'
  authors: Wei Y.
  abstract: Instruction tuning is a supervised fine-tuning approach that significantly improves the ability of large language
    models (LLMs) to follow human instructions. We propose SelfCodeAlign, the first fully transparent and permissive pipeline
    for self-aligning code LLMs without extensive human annotations or distillation. SelfCodeAlign employs the same base model
    for inference throughout the data generation process. It first extracts diverse coding concepts from high-quality seed
    snippets to generate new tasks. It then samples multiple responses per task, pairs each with test cases, and validates
    them in a sandbox environment. Finally, passing examples are selected for instruction tuning. In our primary experiments,
    we use SelfCodeAlign with CodeQwen1.5-7B to generate a dataset of 74k instruction-response pairs. Finetuning on this dataset
    leads to a model that achieves a 67.1 pass@1 on HumanEval+, surpassing CodeLlama-70B-Instruct despite being ten times
    smaller. Across all benchmarks, this finetuned model consistently outperforms the original version trained with OctoPack,
    the previous state-of-the-art method for instruction tuning without human annotations or distillation. Additionally, we
    show that SelfCodeAlign is effective across LLMs of various sizes, from 3B to 33B, and that the base models can benefit
    more from alignment with their own data distribution. We further validate each component's effectiveness in our pipeline,
    showing that SelfCodeAlign outperforms both direct distillation from GPT-4o and leading GPT-3.5-based distillation methods,
    such as OSS-Instruct and Evol-Instruct. SelfCodeAlign has also led to the creation of StarCoder2-Instruct, the first fully
    transparent, permissively licensed, and self-aligned code LLM that achieves state-of-the-art coding performance.
  publisher: Advances in Neural Information Processing Systems.
  published_on: '2024-01-01'
  doi: null
links:
  source: http://arxiv.org/abs/2410.24198v2
  open_access: https://arxiv.org/abs/2410.24198v2
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-06-30T13:29:23.865282Z'
workflow:
  state:
    id: RETRIEVAL/DATABASE_SOUGHT_FOR_RETRIEVAL
    label: Database sought for retrieval
    prisma_bucket: DATABASE_SOUGHT_FOR_RETRIEVAL
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

