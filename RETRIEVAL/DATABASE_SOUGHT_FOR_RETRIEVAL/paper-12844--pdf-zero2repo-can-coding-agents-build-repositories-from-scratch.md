---
schema: paper-monitor/paper/v1
paper_id: 12844
record_type: PAPER
bibliography:
  title: '[PDF] Zero2Repo: Can Coding Agents Build Repositories from Scratch?'
  authors: Pei Yang, Tianyu Shi, Yuhang Yao, Wanyi Chen, Tongyun Yang, Dun Pei, Haonan Wang, Pengbin Feng, Guanxu Yu, Jingchun
    Huang, Zeyu Zhang, Shuhan Sun, Hao Li, Xiang Li, Jie Xiao, Xinyu Wang, Hanxin Chen, Daqi Li, Qi Jia, Hongshan Lin, Zhizhou
    Gu, Zijun Tian, Weizhi Du, Lynn Ai, Eric Yang
  abstract: 'Coding agents are increasingly asked to build software rather than patch it, yet benchmarks for from-scratch
    repository construction are mostly limited to a single language and depend on manually curated tasks. We introduce Zero2Repo,
    a benchmark in which an agent receives a product requirements document, an interface contract, and an empty workspace,
    and must deliver a complete repository in the project''s native ecosystem. Tasks are produced by a language-agnostic authoring
    pipeline that converts real, version-pinned open-source projects into behavioral specifications, reproducible environments,
    and hidden acceptance tests. Each task is validated by execution: a reference implementation derived from the upstream
    project must pass, and adversarial validation must show that the tests reject incorrect implementations. Evaluation runs
    production coding agents in isolated containers, withholds the acceptance tests until an explicit submission, and assigns
    a binary reward only when every test passes, with no LLM judge. The pipeline and harness make no language-specific assumptions
    and apply to mainstream programming ecosystems; the current release contains Python, TypeScript, Go, and C++ tasks. Even
    on 11 tasks drawn from repositories that frontier models have very likely seen during training, the strongest agent solves
    only 10, and every failing submission passes 90-99% of the hidden tests; for the two strongest agents, 67-100% of failed
    tests trace to a single omission or a low-frequency rule stated in the specification rather than to a missing subsystem,
    so each failure is a concrete target for improvement.'
  publisher: arXiv.org.
  published_on: '2026-09-29'
  doi: null
links:
  source: http://arxiv.org/abs/2609.38269v1
  open_access: https://arxiv.org/abs/2609.38269v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-01T09:08:27.686758Z'
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

