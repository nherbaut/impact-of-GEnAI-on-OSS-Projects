---
schema: paper-monitor/paper/v1
paper_id: 6578
record_type: PAPER
bibliography:
  title: '[PDF] FuzzAgent: Multi-Agent System for Evolutionary Library Fuzzing'
  authors: Yunlong Lyu, Peng Chen, Fengyi Wu, Junzhe Yu, Kit Long Hon, Hao Chen
  abstract: 'Library fuzzing is essential for hardening the software supply chain, but adopting it at scale remains expensive.
    Practitioners still spend substantial effort on environment setup, struggle to generate harnesses that respect intricate
    API constraints, and lack reliable means to tell genuine library bugs from harness-induced crashes. Recent LLM-based systems
    automate parts of this pipeline, yet they typically operate as one-shot code generators that ignore runtime feedback,
    which limits both the depth of code they reach and the validity of the bugs they report. We argue that effective library
    fuzzing is iterative by nature: each campaign exposes new coverage bottlenecks and crashes, and the next campaign should
    evolve from these signals rather than restart from scratch. Building on this insight, we present FuzzAgent, a multi-agent
    system that turns library fuzzing into an evolutionary process, in which a team of specialized agents collaborates over
    the full fuzzing lifecycle and grounds every decision in concrete runtime evidence, so that the harness suite is successively
    refined toward deeper coverage and higher-fidelity crash analysis across rounds. We evaluate FuzzAgent on 20 real-world
    C/C++ libraries against four state-of-the-art baselines (OSS-Fuzz, OSS-Fuzz-Gen, PromptFuzz, and PromeFuzz). FuzzAgent
    completes the full fuzzing lifecycle for all 20 libraries without human intervention and reaches 179619 branches, exceeding
    OSS-Fuzz, PromptFuzz, PromeFuzz, and OSS-Fuzz-Gen by 45.1%, 73.2%, 92.1%, and 191.2%, respectively. FuzzAgent also identifies
    102 genuine library bugs, 78 of which have already been acknowledged and fixed by upstream maintainers.'
  publisher: arXiv.org.
  published_on: '2026-05-14'
  doi: null
links:
  source: http://arxiv.org/abs/2605.14431v1
  open_access: https://arxiv.org/abs/2605.14431v1
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

