---
schema: paper-monitor/paper/v1
paper_id: 6591
record_type: PAPER
bibliography:
  title: 'ModSolAgent: Automated Finite Element Code Generation for Abaqus via LLM-Based Agent'
  authors: Zidi Li, Hongwei Ge, Guozhi Tang, Yuxuan Liu
  abstract: Finite element simulation and solution process represents a critical component in engineering analysis. While
    large language models (LLMs) have demonstrated remarkable capabilities in general-purpose code generation from textual
    descriptions, their application to generating structured and specialized finite element simulation scripts presents unique
    challenges. A key challenge is AI-generated hallucination, as these tasks require precise intent analysis, complex planning
    and reasoning, and strict adherence to logical consistency during execution. This often results in outputs that seem convincing
    but are ultimately erroneous. To address this challenge, we propose ModSolAgent, an LLM-based agent that generates Python
    scripts for Abaqus software to perform finite element modeling and solving tasks. ModSolAgent ensures the accuracy and
    logical coherence of code generation by leveraging a structured reasoning instruction, dynamic retrieval guidance template,
    and iterative verification generation. Experimental results demonstrate that LLMs augmented by ModSolAgent achieve an
    83.3% success rate on real-world finite element simulation tasks, effectively meeting most Abaqus scripting requirements
    while significantly outperforming baseline models. To further enhance accessibility, we construct the AbqInstruct dataset
    by distilling knowledge from ModSolAgent to fine-tune the lightweight open-source models. Experiments show that fine-tuning
    on AbqInstruct leads to substantial performance improvements, with the lightweight model achieving proficiency across
    most finite element modeling and solving tasks. This work establishes a paradigm for integrating LLMs with specialized
    engineering software and providing novel insights for other structured, domain-specific code generation scenarios in industrial
    applications.
  publisher: IEEE Transactions on Industrial Informatics
  published_on: '2026-03-23'
  doi: 10.1109/tii.2026.3669495
links:
  source: https://doi.org/10.1109/tii.2026.3669495
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

