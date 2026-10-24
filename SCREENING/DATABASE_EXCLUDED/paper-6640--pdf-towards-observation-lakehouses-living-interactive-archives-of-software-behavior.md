---
schema: paper-monitor/paper/v1
paper_id: 6640
record_type: PAPER
bibliography:
  title: '[PDF] Towards Observation Lakehouses: Living, Interactive Archives of Software Behavior'
  authors: Marcus Kessel
  abstract: 'Code-generating LLMs are trained largely on static artifacts (source, comments, specifications) and rarely on
    materializations of run-time behavior. As a result, they readily internalize buggy or mislabeled code. Since non-trivial
    semantic properties are undecidable in general, the only practical way to obtain ground-truth functionality is by dynamic
    observation of executions. In prior work, we addressed representation with Sequence Sheets, Stimulus-Response Matrices
    (SRMs), and Stimulus-Response Cubes (SRCs) to capture and compare behavior across tests, implementations, and contexts.
    These structures make observation data analyzable offline and reusable, but they do not by themselves provide persistence,
    evolution, or interactive analytics at scale. In this paper, therefore, we introduce observation lakehouses that operationalize
    continual SRCs: a tall, append-only observations table storing every actuation (stimulus, response, context) and SQL queries
    that materialize SRC slices on demand. Built on Apache Parquet + Iceberg + DuckDB, the lakehouse ingests data from controlled
    pipelines (LASSO) and CI pipelines (e.g., unit test executions), enabling n-version assessment, behavioral clustering,
    and consensus oracles without re-execution. On a 509-problem benchmark, we ingest $\approx$8.6M observation rows ($<$51MiB)
    and reconstruct SRM/SRC views and clusters in $<$100ms on a laptop, demonstrating that continual behavior mining is practical
    without a distributed cluster of machines. This makes behavioral ground truth first-class alongside other run-time data
    and provides an infrastructure path toward behavior-aware evaluation and training. The Observation Lakehouse, together
    with the accompanying dataset, is publicly available as an open-source project on GitHub: https://github.com/SoftwareObservatorium/observation-lakehouse'
  publisher: arXiv.org.
  published_on: '2025-12-02'
  doi: null
links:
  source: http://arxiv.org/abs/2512.02795v2
  open_access: https://arxiv.org/abs/2512.02795v2
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

