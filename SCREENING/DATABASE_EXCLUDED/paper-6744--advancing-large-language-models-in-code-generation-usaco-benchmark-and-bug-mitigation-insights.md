---
schema: paper-monitor/paper/v1
paper_id: 6744
record_type: PAPER
bibliography:
  title: 'Advancing Large Language Models in Code Generation: Usaco Benchmark and Bug Mitigation Insights'
  authors: Jacob Trentini, Victor Liu, Yiming Peng, Ziliang Zong
  abstract: Recently, Large Language Models (LLMs) have made substantial progress in code generation, but they still frequently
    generate code containing logic errors or syntax bugs. While research has focused on improving performance through fine-tuning
    and data collection, less attention has been given to analyzing error patterns and employing prompt-engineering to address
    these issues. Existing benchmarks primarily assess LLMs on easy to intermediate-level coding tasks, often neglecting more
    complex challenges involving advanced algorithms and data structures. Additionally, data contamination in these benchmarks
    limits their ability to accurately measure the capability of LLMs in code generation. In this paper, we present the new
    USACO Benchmark, derived from the USA Computing Olympiad (USACO) competition, to evaluate 11 closed and open-source LLMs.
    Through a detailed analysis, we identify common code generation errors across the models and propose Hint-Driven Prompts
    to address logic errors, alongside the Syntax Mitigation Prompt to reduce syntax bugs. Our results demonstrate that the
    Hint-Driven Prompt boosts pass rates for DBRX 132B, Deepseek-Coder 33B, Codegemma 7B, Codellama 7B, Llama 3, and GPT-4o
    by 6.6×, 4.7×, 3×, 2.5×, 2.1×, and 25%, respectively. Additionally, the Syntax Mitigation Prompt significantly reduces
    syntax errors, with reductions of 71.32% for Codegemma 7B, 25.56% for Deepseek-Coder 33B, 23.39% for Llama 3, and 11.19%
    for Codellama 70B.
  publisher: IEEE International Conference on Program Comprehension
  published_on: '2025-04-27'
  doi: 10.1109/icpc66645.2025.00057
links:
  source: https://doi.org/10.1109/icpc66645.2025.00057
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

