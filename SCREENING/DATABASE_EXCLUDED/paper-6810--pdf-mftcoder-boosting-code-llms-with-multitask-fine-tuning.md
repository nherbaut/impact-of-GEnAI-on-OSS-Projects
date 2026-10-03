---
schema: paper-monitor/paper/v1
paper_id: 6810
record_type: PAPER
bibliography:
  title: '[PDF] MFTCoder: Boosting Code LLMs with Multitask Fine-Tuning'
  authors: Bingchang Liu, Chaoyu Chen, Zi Gong, Cong Liao, Huan Wang, Zhichao Lei, Ming Liang, Dajun Chen, Min Shen, Hailian
    Zhou, Wei Jiang, Hang Yu, Jianguo Li
  abstract: Code LLMs have emerged as a specialized research field, with remarkable studies dedicated to enhancing model's
    coding capabilities through fine-tuning on pre-trained models. Previous fine-tuning approaches were typically tailored
    to specific downstream tasks or scenarios, which meant separate fine-tuning for each task, requiring extensive training
    resources and posing challenges in terms of deployment and maintenance. Furthermore, these approaches failed to leverage
    the inherent interconnectedness among different code-related tasks. To overcome these limitations, we present a multi-task
    fine-tuning framework, MFTCoder, that enables simultaneous and parallel fine-tuning on multiple tasks. By incorporating
    various loss functions, we effectively address common challenges in multi-task learning, such as data imbalance, varying
    difficulty levels, and inconsistent convergence speeds. Extensive experiments have conclusively demonstrated that our
    multi-task fine-tuning approach outperforms both individual fine-tuning on single tasks and fine-tuning on a mixed ensemble
    of tasks. Moreover, MFTCoder offers efficient training capabilities, including efficient data tokenization modes and parameter
    efficient fine-tuning (PEFT) techniques, resulting in significantly improved speed compared to traditional fine-tuning
    methods. MFTCoder seamlessly integrates with several mainstream open-source LLMs, such as CodeLLama and Qwen. Our MFTCoder
    fine-tuned CodeFuse-DeepSeek-33B claimed the top spot on the Big Code Models Leaderboard ranked by WinRate as of January
    30, 2024. MFTCoder is open-sourced at https://github.com/codefuse-ai/MFTCOder
  publisher: Proceedings of the ACM SIGKDD International Conference on Knowledge Discovery and Data Mining.
  published_on: '2024-08-24'
  doi: 10.1145/3637528.3671609
links:
  source: https://doi.org/10.1145/3637528.3671609
  open_access: https://dl.acm.org/doi/pdf/10.1145/3637528.3671609
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

