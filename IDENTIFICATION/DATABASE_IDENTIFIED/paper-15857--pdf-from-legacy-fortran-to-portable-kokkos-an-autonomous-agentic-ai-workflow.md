---
schema: paper-monitor/paper/v1
paper_id: 15857
record_type: PAPER
bibliography:
  title: '[PDF] From Legacy Fortran to Portable Kokkos: An Autonomous Agentic AI Workflow'
  authors: Sparsh Gupta, Kamalavasan Kamalakkannan, Maxim Moraru, Galen M Shipman, Patrick Diehl
  abstract: Scientific applications still rely heavily on legacy Fortran codebases built for homogeneous, CPU-based systems.
    As High-Performance Computing (HPC) shifts toward heterogeneous GPU-accelerated architectures, many accelerators lack
    native Fortran bindings, creating a need to translate and optimize legacy code for portability. Frameworks like Kokkos
    offer performance portability through a single-source C++ abstraction, but manual porting from Fortran to Kokkos demands
    significant expertise and remains time-intensive. While large language models (LLMs) show promise in source-to-source
    code generation, their use in autonomous workflows for translating and optimizing parallel code, particularly for performance
    portability across diverse hardware, is largely unexplored. This paper presents an agentic AI workflow in which specialized
    LLM agents collaborate to translate, validate, compile, run, test, debug, and optimize Fortran kernels into portable Kokkos
    C++ programs without human intervention, bounded by configurable retry and optimization thresholds. Because such workflows
    are non-deterministic, we evaluate the pipeline over five runs per configuration on an NVIDIA A100, characterizing its
    variability in success rates, token cost, and optimization behavior. The pipeline modernizes a range of benchmark kernels,
    including a real-world multi-file kernel from a production climate model, into performance-portable Kokkos code across
    hardware partitions. Proprietary models such as GPT-5 and o4-mini-high completed the full workflow most reliably, producing
    optimized code that exceeded the Fortran baselines for only a few U.S. dollars, whereas open-weights models such as gpt-oss-120b
    and Qwen3.5-397B-A17B handled the simpler kernels but struggled with those demanding more complex Kokkos abstractions
    such as parallel reductions and hierarchical parallelism. This work demonstrates, at the kernel level, the feasibility
    of agentic AI for Fortran-to-Kokkos transformation and, more broadly, for structured software-engineering tasks such as
    automated code modernization and refactoring, offering a path toward autonomously modernizing legacy scientific applications
    across diverse supercomputers.
  publisher: IEEE Transactions on Software Engineering.
  published_on: '2026-01-01'
  doi: 10.1109/tse.2026.3752617
links:
  source: https://doi.org/10.1109/tse.2026.3752617
  open_access: https://arxiv.org/pdf/2509.12443
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-11-22T01:55:03.919900Z'
workflow:
  state:
    id: IDENTIFICATION/DATABASE_IDENTIFIED
    label: Database identified
    prisma_bucket: DATABASE_IDENTIFIED
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

