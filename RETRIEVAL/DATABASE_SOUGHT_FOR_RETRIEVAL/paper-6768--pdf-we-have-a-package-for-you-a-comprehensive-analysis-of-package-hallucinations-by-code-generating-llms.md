---
schema: paper-monitor/paper/v1
paper_id: 6768
record_type: PAPER
bibliography:
  title: '[PDF] We Have a Package for You! A Comprehensive Analysis of Package Hallucinations by Code Generating LLMs'
  authors: Spracklen J.
  abstract: 'The reliance of popular programming languages such as Python and JavaScript on centralized package repositories
    and open-source software, combined with the emergence of code-generating Large Language Models (LLMs), has created a new
    type of threat to the software supply chain: package hallucinations. These hallucinations, which arise from fact-conflicting
    errors when generating code using LLMs, represent a novel form of package confusion attack that poses a critical threat
    to the integrity of the software supply chain. This paper conducts a rigorous and comprehensive evaluation of package
    hallucinations across different programming languages, settings, and parameters, exploring how a diverse set of models
    and configurations affect the likelihood of generating erroneous package recommendations and identifying the root causes
    of this phenomenon. Using 16 popular LLMs for code generation and two unique prompt datasets, we generate 576,000 code
    samples in two programming languages that we analyze for package hallucinations. Our findings reveal that that the average
    percentage of hallucinated packages is at least 5.2% for commercial models and 21.7% for open-source models, including
    a staggering 205,474 unique examples of hallucinated package names, further underscoring the severity and pervasiveness
    of this threat. To overcome this problem, we implement several hallucination mitigation strategies and show that they
    are able to significantly reduce the number of package hallucinations while maintaining code quality. Our experiments
    and findings highlight package hallucinations as a persistent and systemic phenomenon while using state-of-the-art LLMs
    for code generation, and a significant challenge which deserves the research community''s urgent attention.'
  publisher: Proceedings of the 34th Usenix Security Symposium.
  published_on: '2025-01-01'
  doi: null
links:
  source: http://arxiv.org/abs/2406.10279v3
  open_access: https://arxiv.org/abs/2406.10279v3
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-06-30T13:29:23.865282Z'
workflow:
  state:
    id: RETRIEVAL/DATABASE_SOUGHT_FOR_RETRIEVAL
    label: Database sought for retrieval
    prisma_bucket: DATABASE_SOUGHT_FOR_RETRIEVAL
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

