---
schema: paper-monitor/paper/v1
paper_id: 15184
record_type: PAPER
bibliography:
  title: '[PDF] MAVCG: Model-Assisted Verified Code Generation from ODD Protocols via Dafny Specifications'
  authors: Patrik Pánczél, László Gulyás
  abstract: 'Large Language Models (LLMs) can generate executable Agent-Based Model (ABM) code from natural-language ODD protocol
    descriptions, yet the resulting implementations are frequently incorrect: they may run without errors but produce statistically
    distinguishable outputs from validated baselines. We present MAVCG, a pipeline that closes this correctness gap by interposing
    a formally verified Dafny specification between the ODD protocol and the generated Python code. MAVCG operates in two
    modes: in Pipeline A each LLM produces its own Dafny specification through iterative Z3 verification; in Pipeline B a
    single pre-verified specification, generated once by a capable model, is supplied to all LLMs as a fixed translation target.
    We evaluate both modes on the PPHPC predator-prey benchmark across 15 models and 90 experiments. Pipeline B lifts three
    models, DeepSeek-V3, Gemma 3 (27B), and Qwen 2.5 Coder (32B), to perfect statistical equivalence (Score 6) on every seed,
    while 9 of 15 models improve over their unverified baselines (mean + 0.38; Score 6 rate from 17.8% to 27.8%). The key
    insight is a practical division of labor: the hard problem of formal specification is solved once, and the resulting mathematical
    constraints guide even small open-source LLMs toward correct, statistically equivalent implementations.'
  publisher: Proceedings of the Intelligent Robotics Fair Introb 2026.
  published_on: '2026-06-18'
  doi: 10.1145/3831600.3831609
links:
  source: https://doi.org/10.1145/3831600.3831609
  open_access: https://doi.org/10.1145/3831600.3831609
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-11-05T01:43:35.005770Z'
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

