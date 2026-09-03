---
schema: paper-monitor/paper/v1
paper_id: 6690
record_type: PAPER
bibliography:
  title: '[PDF] Refactoring Loops in the Era of LLMs: A Comprehensive Study'
  authors: Alessandro Midolo, Emiliano Tramontana
  abstract: Java 8 brought functional programming to the Java language and library, enabling more expressive and concise code
    to replace loops by using streams. Despite such advantages, for-loops remain prevalent in current codebases as the transition
    to the functional paradigm requires a significant shift in the developer mindset. Traditional approaches for assisting
    refactoring loops into streams check a set of strict preconditions to ensure correct transformation, hence limiting their
    applicability. Conversely, generative artificial intelligence (AI), particularly ChatGPT, is a promising tool for automating
    software engineering tasks, including refactoring. While prior studies examined ChatGPT’s assistance in various development
    contexts, none have specifically investigated its ability to refactor for-loops into streams. This paper addresses such
    a gap by evaluating ChatGPT’s effectiveness in transforming loops into streams. We analyzed 2132 loops extracted from
    four open-source GitHub repositories and classified them according to traditional refactoring templates and preconditions.
    We then tasked ChatGPT with the refactoring of such loops and evaluated the correctness and quality of the generated code.
    Our findings revealed that ChatGPT could successfully refactor many more loops than traditional approaches, although it
    struggled with complex control flows and implicit dependencies. This study provides new insights into the strengths and
    limitations of ChatGPT in loop-to-stream refactoring and outlines potential improvements for future AI-driven refactoring
    tools.
  publisher: Future Internet.
  published_on: '2025-09-12'
  doi: 10.3390/fi17090418
links:
  source: https://doi.org/10.3390/fi17090418
  open_access: https://www.mdpi.com/1999-5903/17/9/418/pdf?version=1757926876
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

