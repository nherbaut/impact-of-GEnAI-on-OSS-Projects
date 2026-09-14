---
schema: paper-monitor/paper/v1
paper_id: 6759
record_type: PAPER
bibliography:
  title: '[PDF] LLM Test Generation via Iterative Hybrid Program Analysis'
  authors: Sijia Gu, Noor Nashid, Ali Mesbah
  abstract: Automating unit test generation remains a significant challenge, particularly for complex methods in real-world
    projects. While Large Language Models (LLMs) have made strides in code generation, they struggle to achieve high branch
    coverage due to their limited ability to reason about intricate control flow structures. To address this limitation, we
    introduce Panta, a technique that emulates the iterative process human developers follow when analyzing code and constructing
    test cases. Panta integrates static control flow analysis and dynamic code coverage analysis to systematically guide LLMs
    in identifying uncovered execution paths and generating better test cases. By incorporating an iterative feedback-driven
    mechanism, our technique continuously refines test generation based on static and dynamic path coverage insights, ensuring
    more comprehensive and effective testing. Our empirical evaluation, conducted on classes with high cyclomatic complexity
    from open-source projects, demonstrates that Panta achieves 26% higher line coverage and 23% higher branch coverage compared
    to the state-of-the-art.
  publisher: arXiv.org.
  published_on: '2025-03-17'
  doi: null
links:
  source: http://arxiv.org/abs/2503.13580v2
  open_access: https://arxiv.org/abs/2503.13580v2
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

