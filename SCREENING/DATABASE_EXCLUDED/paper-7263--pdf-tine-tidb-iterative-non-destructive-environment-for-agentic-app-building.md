---
schema: paper-monitor/paper/v1
paper_id: 7263
record_type: PAPER
bibliography:
  title: '[PDF] TINE: TiDB Iterative Non-Destructive Environment for Agentic App Building'
  authors: Hao Huo, Linjie Gao, 迪 Di 王 Wang, Prachi Ray, Jiawen Ding, Xueting Huang, Qizhi Wang
  abstract: 'LLM-based coding agents can generate application code quickly, but demos that ''''build an app from a prompt''''
    often hide the hardest part: data management under iteration. Schema changes, migrations, secrets, and cloud resources
    drift across prompts, making it difficult to reproduce results, roll back, or debug failures. We demonstrate TINE (TiDB
    Iterative Non-Destructive Environment), an open-source, self-hostable control plane for agentic full-stack app building
    that treats every prompt as a versioned, data-backed revision aligned across (i) a Git commit, (ii) a TiDB Cloud database
    branch derived from the previous revision, and (iii) a sandboxed runtime that executes the agent (which may run migrations/backfills/tests)
    and serves a live preview. TINE streams a replayable trace of plans, tool calls, logs, and deploy links, enabling attendees
    to interactively refine an app while preserving runnable historical states. The demo highlights a practical branch-per-instruction
    workflow for safe, reproducible AI-assisted application development.'
  publisher: SIGMOD Companion 2026 Companion of the International Conference on Management of Data.
  published_on: '2026-05-26'
  doi: 10.1145/3788853.3801582
links:
  source: https://doi.org/10.1145/3788853.3801582
  open_access: https://doi.org/10.1145/3788853.3801582
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-07-11T16:48:21.853938Z'
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

