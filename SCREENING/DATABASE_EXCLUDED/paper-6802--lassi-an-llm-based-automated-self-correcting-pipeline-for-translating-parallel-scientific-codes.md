---
schema: paper-monitor/paper/v1
paper_id: 6802
record_type: PAPER
bibliography:
  title: 'LASSI: An LLM-Based Automated Self-Correcting Pipeline for Translating Parallel Scientific Codes'
  authors: Matthew T. Dearing, Yiheng Tao, Xingfu Wu, Zhiling Lan, Valerie Taylor
  abstract: This paper addresses the problem of providing a novel approach to sourcing significant training data for LLMs
    focused on science and engineering. In particular, a crucial challenge is sourcing parallel scientific codes in the ranges
    of millions to billions of codes. To tackle this problem, we propose an automated pipeline framework called LASSI, designed
    to translate between parallel programming languages by bootstrapping existing closed- or open-source LLMs. LASSI incorporates
    autonomous enhancement through self-correcting loops where errors encountered during the compilation and execution of
    generated code are fed back to the LLM through guided prompting for debugging and refactoring. We highlight the bidirectional
    translation of existing GPU benchmarks between OpenMP target offload and CUDA to validate LASSI. The results of evaluating
    LASSI with different application codes across four LLMs demonstrate the effectiveness of LASSI for generating executable
    parallel codes, with 80% of OpenMP to CUDA translations and 85% of CUDA to OpenMP translations producing the expected
    output. We also observe approximately 78% of OpenMP to CUDA translations and 62% of CUDA to OpenMP translations execute
    within 10% of or at a faster runtime than the original benchmark code in the same language.
  publisher: Proceedings 2024 IEEE International Conference on Cluster Computing Workshops Cluster Workshops 2024
  published_on: '2024-09-24'
  doi: 10.1109/clusterworkshops61563.2024.00029
links:
  source: https://doi.org/10.1109/clusterworkshops61563.2024.00029
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

