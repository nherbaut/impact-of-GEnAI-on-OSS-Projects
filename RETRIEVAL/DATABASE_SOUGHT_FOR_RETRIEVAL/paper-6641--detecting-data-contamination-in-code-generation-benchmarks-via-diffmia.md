---
schema: paper-monitor/paper/v1
paper_id: 6641
record_type: PAPER
bibliography:
  title: Detecting Data Contamination in Code Generation Benchmarks via DiffMIA
  authors: Karin Yamashita
  abstract: Data contamination-where benchmark datasets unintentionally appear in the training datasets of large language
    models (LLMs)-poses a critical threat to the validity of model evaluation, especially in code generation. Widely used
    benchmarks such as HumanEval are particularly vulnerable due to their public availability, yet contamination is difficult
    to verify given the proprietary nature of most training data. Conventional membership inference attacks (MIAs) require
    uncontaminated reference datasets, which are often unavailable in benchmark datasets. We propose DiffMIA, a novel method
    for detecting contamination without relying on external clean and untrained data. DiffMIA systematically applies semantics-preserving
    transformations, such as probabilistic variable renaming using CodeBERT, to generate pseudo-uncontaminated samples. By
    analyzing the differential loss values between original and transformed code, we infer whether a model has memorized specific
    benchmark content. Experiments conducted on 7 open-source LLMs demonstrate that DiffMIA can effectively identify contamination
    patterns. The proposed DiffMIA offers a unique solution to validate the reliability of LLM performance evaluations on
    code generation benchmarks.
  publisher: Proceedings Asia Pacific Software Engineering Conference APSEC
  published_on: '2025-12-02'
  doi: 10.1109/apsec66846.2025.00128
links:
  source: https://doi.org/10.1109/apsec66846.2025.00128
  open_access: null
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

