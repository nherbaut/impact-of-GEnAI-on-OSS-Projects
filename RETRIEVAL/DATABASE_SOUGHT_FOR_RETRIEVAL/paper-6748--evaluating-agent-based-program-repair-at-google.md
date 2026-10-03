---
schema: paper-monitor/paper/v1
paper_id: 6748
record_type: PAPER
bibliography:
  title: Evaluating Agent-Based Program Repair at Google
  authors: Pat Rondon, Renyao Wei, José Cambronero, Jürgen Cito, Aaron Sun, Siddhant Sanyam, Michele Tufano, Satish Chandra
  abstract: Agent-based program repair offers to automatically resolve complex bugs end-to-end by combining the planning,
    tool use, and code generation abilities of modern LLMs. Recent work has explored the use of agent-based repair approaches
    on the popular open-source SWE-Bench [1], a collection of bugs from highly-rated GitHub Python projects. In addition,
    various agentic approaches such as SWE-Agent [2] have been proposed to solve bugs in this benchmark. This paper explores
    the viability of using an agentic approach to address bugs in an enterprise context. To investigate this, we curate an
    evaluation set of 178 bugs drawn from Google's issue tracking system. This dataset spans both human-reported (78) and
    machine-reported bugs (100). To establish a repair performance baseline on this benchmark, we implement Passerine, an
    agent similar in spirit to SWE-Agent that can work within Google's development environment. We show that with 20 trajectory
    samples and Gemini 1.5 Pro, Passerine can produce a patch that passes bug tests (i.e., plausible) for 73% of machine-reported
    and 25.6% of human-reported bugs in our evaluation set. After manual examination, we found that 43% of machine-reported
    bugs and 17.9% of human-reported bugs have at least one patch that is semantically equivalent to the ground-truth patch.
    These results establish a baseline on an industrially relevant benchmark, which as we show, contains bugs drawn from a
    different distribution—in terms of language diversity, size, and spread of changes, etc.—compared to those in the popular
    SWE-Bench dataset.
  publisher: IEEE ACM International Conference on Software Engineering Software Engineering in Practice
  published_on: '2025-04-27'
  doi: 10.1109/icse-seip66354.2025.00038
links:
  source: https://doi.org/10.1109/icse-seip66354.2025.00038
  open_access: null
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

