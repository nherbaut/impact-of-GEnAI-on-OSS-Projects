---
schema: paper-monitor/paper/v1
paper_id: 6776
record_type: PAPER
bibliography:
  title: '[PDF] VisCoder: Fine-Tuning LLMs for Executable Python Visualization Code Generation'
  authors: Yuansheng Ni, Ping Nie, Kai Zou, Xiang Yue, Wenhu Chen
  abstract: 'Large language models (LLMs) often struggle with visualization tasks like plotting diagrams, charts, where success
    depends on both code correctness and visual semantics.Existing instruction-tuning datasets lack executiongrounded supervision
    and offer limited support for iterative code correction, resulting in fragile and unreliable plot generation.We present
    VisCode-200K, a large-scale instruction tuning dataset for Python-based visualization and self-correction.It contains
    over 200K examples from two sources: (1) validated plotting code from open-source repositories, paired with natural language
    instructions and rendered plots; and (2) 45K multi-turn correction dialogues from Code-Feedback, enabling models to revise
    faulty code using runtime feedback.We fine-tune Qwen2.5-Coder-Instruct on VisCode-200K to create VisCoder, and evaluate
    it on PandasPlotBench.VisCoder significantly outperforms strong open-source baselines and approaches the performance of
    proprietary models like GPT-4o-mini.We further adopt a selfdebug evaluation protocol to assess iterative repair, demonstrating
    the benefits of feedbackdriven learning for executable, visually accurate code generation.'
  publisher: Emnlp 2025 2025 Conference on Empirical Methods in Natural Language Processing Findings of Emnlp 2025.
  published_on: '2025-01-01'
  doi: 10.18653/v1/2025.findings-emnlp.160
links:
  source: https://doi.org/10.18653/v1/2025.findings-emnlp.160
  open_access: https://aclanthology.org/2025.findings-emnlp.160.pdf
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

