---
schema: paper-monitor/paper/v1
paper_id: 6562
record_type: PAPER
bibliography:
  title: '[PDF] Evaluating LLMs on Real-World Software Performance Optimization'
  authors: Ezgi Sarıkayak, Wenchao Gu, Hesham Ghonim, Chunyang Chen
  abstract: 'Software performance optimization is a notoriously complex and manual task. Despite the growing use of Large
    Language Models (LLMs) for code refinement, we still lack benchmarks that capture how optimization actually happens in
    real-world codebases. Existing frameworks often oversimplify the problem by focusing on isolated functions or a single
    performance metric, missing the critical trade-offs between execution time and memory footprint, the inherent noise of
    the measurement environment, and the variability introduced by different input data and execution conditions. We address
    this by introducing SWE-Pro, a repository-level benchmark derived from 102 expert-written optimizations from open-source
    projects. Unlike previous benchmarks, SWE-Pro pairs each task with parameterized tests to evaluate runtime, peak memory,
    and Time-Weighted Memory Usage (TWMU) across varying input data and execution conditions under noise-aware measurement
    conditions. Our evaluation shows that current LLMs struggle significantly: runtime gains are negligible, and memory optimizations
    are nearly non-existent. This stands in sharp contrast to expert implementations, which achieve an aggregate speedup of
    15.5x and peak memory reduction of 171.3x over benchmark tasks. Expert-written improvements are observed in 91.2% of tasks
    for runtime and 65.7% for peak memory. Our findings expose a substantial gap between current LLM capabilities and the
    demands of expert-level engineering.'
  publisher: arXiv.org.
  published_on: '2026-06-24'
  doi: null
links:
  source: http://arxiv.org/abs/2606.25530v1
  open_access: https://arxiv.org/abs/2606.25530v1
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

