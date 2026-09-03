---
schema: paper-monitor/paper/v1
paper_id: 6740
record_type: PAPER
bibliography:
  title: 'Too Noisy To Learn: Enhancing Data Quality for Code Review Comment Generation'
  authors: Chunhua Liu, Hong Yi Lin, Patanamon Thongtanunam
  abstract: Code review is an important practice in software development, yet it is time-consuming and requires substantial
    effort. While open-source datasets have been used to train neural models for automating code review tasks, including review
    comment generation, these datasets contain a significant amount of noisy comments (e.g., vague or non-actionable feedback)
    that persist despite cleaning methods using heuristics and machine learning approaches. Such remaining noise may lead
    models to generate low-quality review comments, yet removing them requires a complex semantic understanding of both code
    changes and natural language comments. In this paper, we investigate the impact of such noise on review comment generation
    and propose a novel approach using large language models (LLMs) to further clean these datasets. Based on an empirical
    study on a large-scale code review dataset, our LLM-based approach achieves $66-85 \%$ precision in detecting valid comments.
    Using the predicted valid comments to fine-tune the state-of-the-art code review models (cleaned models) can generate
    review comments that are $13.0 \%-12.4 \%$ more similar to valid human-written comments than the original models. We also
    find that the cleaned models can generate more informative and relevant comments than the original models. Our findings
    underscore the critical impact of dataset quality on the performance of review comment generation. We advocate for further
    research into cleaning training data to enhance the practical utility and quality of automated code review.
  publisher: Proceedings 2025 IEEE ACM 22nd International Conference on Mining Software Repositories MSR 2025
  published_on: '2025-04-28'
  doi: 10.1109/msr66628.2025.00043
links:
  source: https://doi.org/10.1109/msr66628.2025.00043
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

