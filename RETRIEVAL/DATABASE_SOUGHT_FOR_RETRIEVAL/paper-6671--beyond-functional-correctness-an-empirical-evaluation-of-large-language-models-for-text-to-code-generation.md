---
schema: paper-monitor/paper/v1
paper_id: 6671
record_type: PAPER
bibliography:
  title: 'Beyond Functional Correctness: An Empirical Evaluation of Large Language Models for Text-to-Code Generation'
  authors: Rodrigo Nogueira, Marco Vieira, João R. Campos
  abstract: Large Language Models (LLMs) have become increasingly popular for text-to-code generation, a task that involves
    converting natural language descriptions into code. While they have shown promising results, they are still flawed, especially
    when dealing with complex problems, making it crucial to have a deep understanding of their strengths and limitations.
    However, current evaluations are often limited, targeting only a single programming language, considering a small set
    of related models, and focusing heavily on execution-based metrics such as unit test pass rates. Moreover, they tend to
    overlook deeper issues like code quality, recurring mistakes, and underlying patterns in the generated code. To address
    these gaps and properly assess how effective LLMs are at generating quality code, we conduct a comprehensive evaluation
    of several LLMs across Python and C++ using a large, diverse dataset that spans multiple difficulty levels. Our evaluation
    combines execution-based and static analysis metrics, enabling us to assess both functional correctness and the structural
    quality of the code. Unlike prior work, our study also includes an in-depth analysis of the generated code, uncovering
    common mistakes and failure modes, allowing for a more complete and differentiated view of model capabilities. Results
    show that, despite their potential, open-source LLMs still struggle with complex tasks and make recurring systematic errors
    such as missing import statements and incorrect variable scoping.
  publisher: Proceedings International Symposium on Software Reliability Engineering ISSRE
  published_on: '2025-10-21'
  doi: 10.1109/issre66568.2025.00036
links:
  source: https://doi.org/10.1109/issre66568.2025.00036
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

