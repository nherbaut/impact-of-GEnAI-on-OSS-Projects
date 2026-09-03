---
schema: paper-monitor/paper/v1
paper_id: 8372
record_type: PAPER
bibliography:
  title: '[PDF] Optimizing Context and Cost in LLM ‐Based Unit Test Generation: A Study on External Dependency Retrieval Strategies'
  authors: Javier Ferrer, Francisco Chicano
  abstract: ABSTRACT While Large Language Models (LLMs) have demonstrated remarkable capabilities in code generation, their
    effectiveness in unit testing is often constrained by insufficient context regarding external dependencies. This limitation
    is particularly pronounced in industrial settings, where proprietary code remains opaque to the model. To address this
    challenge, we present a systematic empirical study of multiple strategies for context enrichment and optimization in LLM‐based
    unit test generation, conducted on seven diverse projects (three open‐source and four proprietary industrial systems),
    encompassing 261 distinct methods. By evaluating seven implementations (ranging from basic prompts to optimized context
    reduction strategies) across 10 independent runs, we analysed a total of 28,710 test suites. Our results demonstrate that
    combining prompt engineering with external dependency retrieval achieves an average branch coverage increase of 11.52
    percentage points on industrial software over the baseline, with statistically significant improvements across all competing
    implementations. Beyond coverage, richer context substantially reduces generation‐repair iterations, cutting median execution
    time by 51.3% in industrial projects. We further show that reducing external dependencies to method signatures alone decreases
    input token consumption by up to 46.6% (25.4% in industrial projects) while fully preserving the coverage and efficiency
    gains of the complete retrieval approach. To confirm that these benefits are not tied to a specific model, we replicate
    the core comparison across three LLM backends from different families, obtaining a consistent, statistically significant
    coverage improvement on industrial code in every case. These findings establish this optimized context strategy as a cost‐effective
    solution for scalable, industrial‐grade automated test generation.
  publisher: Expert Systems.
  published_on: '2026-08-25'
  doi: 10.1111/exsy.70401
links:
  source: https://doi.org/10.1111/exsy.70401
  open_access: https://onlinelibrary.wiley.com/doi/pdfdirect/10.1111/exsy.70401
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-09-03T07:20:34.064167Z'
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

