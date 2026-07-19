---
schema: paper-monitor/paper/v1
paper_id: 6769
record_type: PAPER
bibliography:
  title: '[PDF] Tree-of-Evolution: Tree-Structured Instruction Evolution for Code Generation in Large Language Models'
  authors: Ziyang Luo, Kaixin Li, Hongzhan Lin, Yuchen Tian, Mohan Kankanhalli, Jing Ma
  abstract: Data synthesis has become a crucial research area in large language models (LLMs), especially for generating high-quality
    instruction fine-tuning data to enhance downstream performance.In code generation, a key application of LLMs, manual annotation
    of code instruction data is costly.Recent methods, such as Code Evol-Instruct and OSS-Instruct, leverage LLMs to synthesize
    large-scale code instruction data, significantly improving LLM coding capabilities.However, these approaches face limitations
    due to unidirectional synthesis and randomness-driven generation, which restrict data quality and diversity.To overcome
    these challenges, we introduce Tree-of-Evolution (ToE), a novel framework that models code instruction synthesis process
    with a tree structure, exploring multiple evolutionary paths to alleviate the constraints of unidirectional generation.Additionally,
    we propose optimizationdriven evolution, which refines each generation step based on the quality of the previous iteration.Experimental
    results across five widely-used coding benchmarks-HumanEval, MBPP, EvalPlus, LiveCodeBench, and Big-CodeBench-demonstrate
    that base models fine-tuned on just 75k data synthesized by our method achieve comparable or superior performance to the
    state-of-the-art open-weight Code LLM, Qwen2.5-Coder-Instruct, which was finetuned on millions of samples.
  publisher: Proceedings of the Annual Meeting of the Association for Computational Linguistics.
  published_on: '2025-01-01'
  doi: 10.18653/v1/2025.acl-long.14
links:
  source: https://doi.org/10.18653/v1/2025.acl-long.14
  open_access: https://aclanthology.org/2025.acl-long.14.pdf
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

