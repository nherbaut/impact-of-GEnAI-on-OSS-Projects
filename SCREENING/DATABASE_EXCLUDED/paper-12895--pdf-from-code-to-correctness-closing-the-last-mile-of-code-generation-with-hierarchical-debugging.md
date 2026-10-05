---
schema: paper-monitor/paper/v1
paper_id: 12895
record_type: PAPER
bibliography:
  title: '[PDF] From Code to Correctness: Closing the Last Mile of Code Generation with Hierarchical Debugging'
  authors: Yuling Shi, S. ShouHan Wang, Chengcheng Wan, Min Wang, Xiaodong Gu
  abstract: While large language models have made significant strides in code generation, the pass rate of the generated code
    is bottlenecked on subtle errors, often requiring human intervention to pass tests, especially for complex problems. Existing
    LLM-based debugging systems treat generated programs as monolithic units, failing to address bugs at multiple levels of
    granularity, from low-level syntax errors to high-level algorithmic flaws. In this paper, we introduce Multi-Granularity
    Debugger (MGDebugger), a hierarchical code debugger by isolating, identifying, and resolving bugs at various levels of
    granularity. MGDebugger decomposes problematic code into a hierarchical tree structure of subfunctions, with each level
    representing a particular granularity of error. During debugging, it analyzes each subfunction and iteratively resolves
    bugs in a bottom-up manner. To effectively test each subfunction, we propose an LLM-simulated Python executor, which traces
    code execution and tracks important variable states to pinpoint errors accurately. Extensive experiments demonstrate that
    MGDebugger outperforms existing debugging systems, achieving an 18.9% improvement in accuracy over seed generations in
    HumanEval and a 97.6% repair success rate in HumanEvalFix. Furthermore, MGDebugger effectively fixes bugs across different
    categories and difficulty levels, demonstrating its robustness and effectiveness.
  publisher: Proceedings 2026 IEEE ACM 48th International Conference on Software Engineering ICSE 2026.
  published_on: '2026-04-12'
  doi: 10.1145/3744916.3773255
links:
  source: https://doi.org/10.1145/3744916.3773255
  open_access: https://doi.org/10.1145/3744916.3773255
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-04T12:14:22.898402Z'
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

