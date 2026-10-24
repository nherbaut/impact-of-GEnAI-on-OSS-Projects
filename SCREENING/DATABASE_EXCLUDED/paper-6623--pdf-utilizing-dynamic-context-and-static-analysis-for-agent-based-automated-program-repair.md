---
schema: paper-monitor/paper/v1
paper_id: 6623
record_type: PAPER
bibliography:
  title: '[PDF] Utilizing Dynamic Context and Static Analysis for Agent-Based Automated Program Repair'
  authors: Aslan Safarovich Abdinabiev, Eunseo Jung, Byungjeong Lee
  abstract: Automated Program Repair (APR) addresses the challenge of reducing software maintenance costs and improving software
    reliability. While recent advances in Large Language Models (LLMs) achieved measurable improvements in code generation
    tasks, their application to program repair faces specific challenges including limited context awareness, repetitive patch
    generation, and inability to learn from failed repair attempts. In this paper, we present a novel agent-based automated
    program repair approach that orchestrates specialized LLM agents with dynamic context management to iteratively refine
    and generate patches. Our approach introduces an agent-based architecture with a Context Updater, a Generator, and an
    Overfitting Detector, which work together with a comprehensive static analysis tool suite to gather relevant repair context,
    generate diverse patches, learn from failed attempts, and prevent overfitting solutions. The architecture employs a vector
    database powered by an embedding model for semantic code search, maintains a context pool (static and dynamic modules)
    for context management, and implements intelligent hypothesis tracking to avoid redundant repairs. We evaluate our approach
    on Defects4J and SWE-Bench Lite with multiple LLM backends under both perfect and automated fault localization settings.
    Our approach correctly fixes up to 365 and 87 bugs on Defects4J and SWE-Bench Lite respectively, generalizes across models,
    with open-source models achieving up to 252 correct fixes, and retains 69.7% of perfect-FL performance under automated
    fault localization. The approach is particularly effective on complex multi-function bugs, fixing up to 53 on Defects4J
    and 10 on SWE-Bench Lite.
  publisher: IEEE Access.
  published_on: '2026-01-01'
  doi: 10.1109/access.2026.3691783
links:
  source: https://doi.org/10.1109/access.2026.3691783
  open_access: https://doi.org/10.1109/access.2026.3691783
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

