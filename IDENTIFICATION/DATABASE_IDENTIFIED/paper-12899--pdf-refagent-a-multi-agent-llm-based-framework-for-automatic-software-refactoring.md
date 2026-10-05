---
schema: paper-monitor/paper/v1
paper_id: 12899
record_type: PAPER
bibliography:
  title: '[PDF] RefAgent: A Multi-agent LLM-based Framework for Automatic Software Refactoring'
  authors: Khouloud Oueslati, Maxime Lamothe, Foutse Khomh
  abstract: Recent progress in Large Language Models (LLMs) has influenced various software engineering tasks, including code
    generation, program repair, and software maintenance. Indeed, in the case of software refactoring, traditional LLMs have
    shown the ability to reduce development time and enhance code quality. However, these LLMs often rely on static, detailed
    instructions for specific tasks. In contrast, LLM-based agents can dynamically adapt to evolving contexts and autonomously
    make decisions by interacting with software tools and executing workflows. In this paper, we explore the potential of
    LLM-based agents in supporting refactoring activities. Specifically, we introduce RefAgent, a multi-agent LLM-based framework
    for end-to-end software refactoring. RefAgent consists of specialized agents responsible for planning, executing, testing,
    and iteratively refining refactorings using self-reflection and tool-calling capabilities. We evaluate RefAgent on eight
    open-source Java projects, comparing its effectiveness against a single-agent approach, a search-based refactoring tool,
    and historical developer refactorings. Our results show that RefAgent achieves a median unit test pass rate of 90%, reduces
    code smells by a median of 52.5%, and improves key quality attributes (e.g., reusability) by a median of 8.6%. Additionally,
    it closely aligns with developer refactorings and the search-based tool in identifying refactoring opportunities, attaining
    a median F1-score of 79.15% and 72.7%, respectively. Compared to single-agent approaches, RefAgent improves the median
    unit test pass rate by 64.7% and the median compilation success rate by 40.1%. These findings highlight the promise of
    multi-agent architectures in advancing automated software refactoring.
  publisher: Proceedings 2026 IEEE ACM 48th International Conference on Software Engineering ICSE 2026.
  published_on: '2026-04-12'
  doi: 10.1145/3744916.3773153
links:
  source: https://doi.org/10.1145/3744916.3773153
  open_access: https://doi.org/10.1145/3744916.3773153
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

