---
schema: paper-monitor/paper/v1
paper_id: 6635
record_type: PAPER
bibliography:
  title: 'AdaCoder: An Adaptive Planning and Multi-Agent Framework for Function-Level Code Generation'
  authors: Yueheng Zhu, Chao Liu, Xuan He, Xiaoxue Ren, Zhongxin Liu, Ruwei Pan, Hongyu Zhang
  abstract: Recently, researchers have proposed many multi-agent frameworks for function-level code generation, which aim
    to improve software development productivity by automatically generating function-level source code based on task descriptions.
    A typical multi-agent framework consists of Large Language Model (LLM)-based agents that are responsible for task planning,
    code generation, testing, debugging, etc. Studies have shown that existing multi-agent code generation frameworks perform
    well on ChatGPT. However, their generalizability across other foundation LLMs remains unexplored systematically. In this
    paper, we report an empirical study on the generalizability of four state-of-the-art multi-agent code generation frameworks
    across 12 open-source LLMs with varying code generation and instruction-following capabilities. Our study reveals the
    unstable generalizability of existing frameworks on diverse foundation LLMs. Based on the findings obtained from the empirical
    study, we propose AdaCoder, a novel adaptive planning, multi-agent framework for function-level code generation. AdaCoder
    has two phases. Phase-1 is an initial code generation step without planning, which uses an LLM-based coding agent and
    a script-based testing agent to unleash LLM’s native power, identify cases beyond LLM’s power, and determine the errors
    hindering execution. Phase-2 adds a rule-based debugging agent and an LLM-based planning agent for iterative code generation
    with planning. Our evaluation shows that AdaCoder achieves higher generalizability on diverse LLMs. Compared to the best
    baseline MapCoder, AdaCoder is on average 27.69% higher in Pass@1, 16 times faster in inference, and 12 times lower in
    token consumption.
  publisher: IEEE Transactions on Software Engineering
  published_on: '2025-12-12'
  doi: 10.1109/tse.2025.3642621
links:
  source: https://doi.org/10.1109/tse.2025.3642621
  open_access: null
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

