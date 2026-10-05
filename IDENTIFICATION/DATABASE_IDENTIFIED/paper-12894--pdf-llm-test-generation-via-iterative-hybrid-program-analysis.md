---
schema: paper-monitor/paper/v1
paper_id: 12894
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
  publisher: Proceedings 2026 IEEE ACM 48th International Conference on Software Engineering ICSE 2026.
  published_on: '2026-04-12'
  doi: 10.1145/3744916.3764553
links:
  source: https://doi.org/10.1145/3744916.3764553
  open_access: https://doi.org/10.1145/3744916.3764553
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-04T12:14:22.898402Z'
workflow:
  state:
    id: IDENTIFICATION/DATABASE_IDENTIFIED
    label: Database identified
    prisma_bucket: DATABASE_IDENTIFIED
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

