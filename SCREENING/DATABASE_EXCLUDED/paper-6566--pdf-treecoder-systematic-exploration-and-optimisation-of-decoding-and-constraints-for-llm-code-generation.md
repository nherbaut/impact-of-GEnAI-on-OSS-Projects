---
schema: paper-monitor/paper/v1
paper_id: 6566
record_type: PAPER
bibliography:
  title: '[PDF] TreeCoder: Systematic Exploration and Optimisation of Decoding and Constraints for LLM Code Generation'
  authors: Henrijs Princis, Arindam Sharma, Cristina David
  abstract: Large language models (LLMs) have shown remarkable ability to generate code, yet their outputs often violate syntactic
    or semantic constraints when guided only through natural language prompts. We introduce TreeCoder, the most general and
    flexible framework to date for exploring decoding strategies, constraints, and hyperparameters in LLMs, and use it in
    code generation to enforce correctness and structure during decoding rather than relying on prompt engineering. TreeCoder
    represents decoding as a tree search over candidate programs, where both decoding strategies and constraint functions–such
    as style, syntax, execution–are treated as first-class, optimisable components. This design enables systematic exploration
    and automatic tuning of decoding configurations using standard optimisation techniques. Experiments on Python, SQL and
    Rust show that TreeCoder consistently improves accuracy across open-source models such as CodeLlama, Mistral, DeepSeek
    and Qwen, often significantly outperforming their unconstrained baselines.
  publisher: Proceedings of the ACM on Programming Languages.
  published_on: '2026-06-08'
  doi: 10.1145/3808347
links:
  source: https://doi.org/10.1145/3808347
  open_access: https://doi.org/10.1145/3808347
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

