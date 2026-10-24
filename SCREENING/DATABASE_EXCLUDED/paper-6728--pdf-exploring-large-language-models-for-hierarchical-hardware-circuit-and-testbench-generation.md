---
schema: paper-monitor/paper/v1
paper_id: 6728
record_type: PAPER
bibliography:
  title: '[PDF] Exploring Large Language Models for Hierarchical Hardware Circuit and Testbench Generation'
  authors: Samuel Gomes Lopes, Shien Zhu, Gustavo Alonso
  abstract: 'Designing and verifying hardware circuits using a Hardware Description Language (HDL) is an essential but time-consuming
    part of hardware design. Generating the desired correct circuit and testbench code usually requires a significant engineering
    effort. Recently, Large Language Models (LLMs) have claimed to have strong code generation capabilities to reduce such
    engineering costs. Existing work has provided quantitative evaluations using LLMs for single-module, simple circuit generation.
    However, it is still unclear whether modern LLMs are useful in production workflows, e.g., generating correct hierarchical
    circuits with testbenches. And if they are capable, what are the best prompt engineering practices for hardware design?
    In this article, we evaluate LLMs for HDL generation by exploring a 3-dimensional design space: commercial and open-source
    language models, single-module and hierarchical circuits, and prompting methods with varying complexity. We propose a
    3-step design space exploration methodology to answer the two aforementioned questions. First, we explore the best prompt
    engineering practices across generating simple, middle, and hard single-module circuits with testbenches on CodeLLama-34B.
    We also define two fine-grained checklists to evaluate the circuit and testbench quality from a user’s perspective. Second,
    we benchmark 11 LLMs with prompt adaptation on 4 single-module circuits that CodeLLama-34B has trouble with to further
    find models that may be useful in a production workflow. Third, we apply the learned prompt practices on four top-level
    models to generate simple 2 to 4-module and more complex multi-module hierarchical circuits and testbenches. As a result,
    we find that some of the latest LLMs can generate correct simple hierarchical circuits and testbenches with given proper
    prompts, but still struggle with complex hierarchical circuits. We further provide useful guidelines from an end-user’s
    perspective on leveraging LLMs for hardware design.'
  publisher: ACM Transactions on Design Automation of Electronic Systems.
  published_on: '2025-06-04'
  doi: 10.1145/3742430
links:
  source: https://doi.org/10.1145/3742430
  open_access: https://doi.org/10.1145/3742430
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

