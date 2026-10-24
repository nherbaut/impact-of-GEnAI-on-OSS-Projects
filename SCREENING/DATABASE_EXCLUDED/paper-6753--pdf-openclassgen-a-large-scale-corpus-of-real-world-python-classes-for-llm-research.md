---
schema: paper-monitor/paper/v1
paper_id: 6753
record_type: PAPER
bibliography:
  title: '[PDF] OpenClassGen: A Large-Scale Corpus of Real-World Python Classes for LLM Research'
  authors: Musfiqur Rahman, SayedHassan Khatoonabadi, Emad Shihab
  abstract: 'Existing class-level code generation datasets are either synthetic (ClassEval: 100 classes) or insufficient in
    scale for modern training needs (RealClassEval: 400 classes), hindering robust evaluation and empirical analysis. We present
    OpenClassGen, a large-scale corpus of 324,843 Python classes extracted from 2,970 engineered open-source projects. Each
    entry pairs a human-written class with its corresponding skeleton, which comprises class and method signatures with associated
    docstrings, and is enriched with 27 static code metrics covering complexity, coupling, cohesion, and inheritance properties.
    Unlike prior benchmarks that require repository-level context resolution, OpenClassGen provides self-contained class skeletons
    that serve as complete generation specifications. We demonstrate the corpus''s utility by evaluating three LLMs (GPT-o4-mini,
    Claude-4-Sonnet, Qwen-3-Coder) on a curated, executable subset of 300 classes, enriched with test suites achieving 58%
    branch coverage. Results show strong semantic similarity (CodeBERTScore-F3: 0.89) but moderate functional correctness
    (pass rate: 0.33), with substantial variance across models. This variance, along with diverse class characteristics, confirms
    that OpenClassGen enables meaningful differentiation of LLM capabilities. The dataset supports diverse use cases, including
    fine-tuning, retrieval-augmented generation, difficulty modelling, and failure mode analysis. The complete dataset and
    curation scripts are publicly available at https://zenodo.org/records/18409150.'
  publisher: arXiv.org.
  published_on: '2025-04-22'
  doi: null
links:
  source: http://arxiv.org/abs/2504.15564v3
  open_access: https://arxiv.org/abs/2504.15564v3
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

