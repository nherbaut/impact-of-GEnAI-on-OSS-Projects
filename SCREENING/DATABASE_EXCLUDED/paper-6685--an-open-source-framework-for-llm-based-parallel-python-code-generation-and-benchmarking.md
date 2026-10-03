---
schema: paper-monitor/paper/v1
paper_id: 6685
record_type: PAPER
bibliography:
  title: An Open-Source Framework for LLM-Based Parallel Python Code Generation and Benchmarking
  authors: Pankaj Siri Bharath Bairu, David Alfred Ostrowski
  abstract: Organizations are increasingly exploring the integration of Generative AI (GenAI) into software engineering workflows.
    Despite the promise of improved productivity, the challenge of generating correct, parallelized, and testable code remains
    a significant barrier to adoption. This paper introduces a framework for parallel-aware code generation and evaluation,
    built on local large language models (LLMs) orchestrated with open-source infrastructure. The system curates prompts from
    MBPP tasks and custom-designed computational kernels, generates code with explicit vectorization and multiprocessing constraints,
    validates correctness, and benchmarks runtime speedups against sequential baselines. Experiments on 20 workloads—10 kernel
    benchmarks (e.g., GEMM, FFT, Conv2D, BFS) and 10 MBPP tasks—demonstrate that correctness is preserved while measurable
    speedups are achieved, particularly for computationally intensive workloads. Results highlight that performance gains
    depend heavily on workload size, type, and available compute resources. Notably, speedup was observable even when running
    on a personal PC, underscoring the reproducibility of the framework. This work contributes a methodology and open-source
    pipeline that foregrounds both correctness and efficiency in LLM-based software synthesis.
  publisher: Proceedings 2025 International Conference on AI X Software Engineering Aixse 2025
  published_on: '2025-10-01'
  doi: 10.1109/aixse64906.2025.00018
links:
  source: https://doi.org/10.1109/aixse64906.2025.00018
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

