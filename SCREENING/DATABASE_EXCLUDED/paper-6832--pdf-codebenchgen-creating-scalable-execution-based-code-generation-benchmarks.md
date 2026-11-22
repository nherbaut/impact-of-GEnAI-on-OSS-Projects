---
schema: paper-monitor/paper/v1
paper_id: 6832
record_type: PAPER
bibliography:
  title: '[PDF] CodeBenchGen: Creating Scalable Execution-based Code Generation Benchmarks'
  authors: Yiqing Xie, Alex Xie, Divyanshu Sheth, Pengfei Liu, Daniel Fried, Carolyn Rose
  abstract: 'To adequately test modern code generation systems, evaluation benchmarks must execute and test the code generated
    by the system. However, these execution and testing requirements have largely limited benchmarks to settings where code
    is easily executable or has human-written tests. To facilitate evaluation of code generation systems across diverse scenarios,
    we present CodeBenchGen, a framework to create scalable execution-based benchmarks from naturally occurring code sources.
    Specifically, we leverage a large language model (LLM) to sandbox arbitrary pieces of code into evaluation examples, including
    test cases for execution-based evaluation. We illustrate the usefulness of our framework by creating a dataset, Exec-CSN,
    which includes 1,931 examples involving 293 libraries converted from code in 367 GitHub repositories taken from the Code-
    SearchNet dataset. To demonstrate the solvability of examples in Exec-CSN, we present a human study demonstrating that
    81.3% of the examples can be solved by humans and 61% are rated as "requires effort to solve". We conduct code generation
    experiments on open-source and proprietary models and analyze the performance of both humans and models. We provide code
    and data at: https://github.com/yiqingxyq/CodeBenchGen.'
  publisher: arXiv.org.
  published_on: '2024-03-31'
  doi: null
links:
  source: http://arxiv.org/abs/2404.00566v4
  open_access: https://arxiv.org/abs/2404.00566v4
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

