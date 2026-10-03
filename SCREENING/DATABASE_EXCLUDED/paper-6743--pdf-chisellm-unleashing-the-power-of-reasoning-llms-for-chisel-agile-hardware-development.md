---
schema: paper-monitor/paper/v1
paper_id: 6743
record_type: PAPER
bibliography:
  title: '[PDF] ChiseLLM: Unleashing the Power of Reasoning LLMs for Chisel Agile Hardware Development'
  authors: Bowei Wang, Jiaran Gao, Yelai Feng, Renzhi Chen, Shanshan Li, Lei Wang
  abstract: 'The growing demand for Domain-Specific Architecture (DSA) has driven the development of Agile Hardware Development
    Methodology (AHDM). Hardware Construction Language (HCL) like Chisel offers high-level abstraction features, making it
    an ideal language for HCL-Based AHDM. While Large Language Models (LLMs) excel in code generation tasks, they still face
    challenges with Chisel generation, particularly regarding syntax correctness and design variability. Recent reasoning
    models have significantly enhanced code generation capabilities through test-time scaling techniques. However, we found
    that reasoning models without domain adaptation cannot bring substantial benefits to Chisel code generation tasks. This
    paper presents ChiseLLM, a solution comprising data processing and transformation, prompt-guided reasoning trace synthesis,
    and domain-adapted model training. We constructed high-quality datasets from public RTL code resources and guided the
    model to adopt structured thinking patterns through prompt enhancement methods. Experiments demonstrate that our ChiseLLM-7B
    and ChiseLLM-32B models improved syntax correctness by 18.85% and 26.32% respectively over base models, while increasing
    variability design ability by 47.58% compared to baseline reasoning models. Our datasets and models are publicly available,
    providing high-performance, cost-effective models for HCL-Based AHDM, and offering an effective baseline for future research.
    Github repository: https://github.com/observerw/ChiseLLM'
  publisher: arXiv.org.
  published_on: '2025-04-27'
  doi: null
links:
  source: http://arxiv.org/abs/2504.19144v1
  open_access: https://arxiv.org/abs/2504.19144v1
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

