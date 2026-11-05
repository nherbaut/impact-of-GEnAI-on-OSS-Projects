---
schema: paper-monitor/paper/v1
paper_id: 6693
record_type: PAPER
bibliography:
  title: 'LASSO: LLM-Aided Security Property Generation for Assertion-based SoC Verification'
  authors: Dinesh Reddy Ankireddy, Sudipta Paria, Aritra Dasgupta, Sandip Ray, Swarup Bhunia
  abstract: Ensuring the security of modern System-on-Chip (SoC) designs poses significant challenges due to increasing complexity
    and distributed assets across the intellectual property (IP) blocks. Formal property verification (FPV) provides the capability
    to model and validate design behaviors through security properties with model checkers; however, current practices require
    significant manual efforts to create such properties, making them time-consuming, costly, and error-prone. The emergence
    of Large Language Models (LLMs) has showcased remarkable proficiency across diverse domains, including HDL code generation
    and verification tasks. Current LLM-based techniques often produce vacuous assertions and lack efficient prompt generation,
    comprehensive verification, and bug detection. This paper presents LASSO, a novel framework that leverages LLMs and retrieval-augmented
    generation (RAG) to produce non-vacuous security properties and SystemVerilog Assertions (SVA) from design specifications
    and related documentation for bus-based SoC designs. LASSO integrates commercial EDA tool for FPV to generate standard
    coverage metrics and iteratively refines prompts through a feedback loop to enhance coverage. The effectiveness of LASSO
    is validated through various open-source SoC designs, demonstrating high coverage values with an average of ~88% denoting
    comprehensive verification through efficient generation of security properties and SVAs. LASSO also demonstrates bug detection
    capabilities, identifying five unique bugs in the buggy OpenTitan SoC from Hack@DAC’24 competition.
  publisher: 2025 ACM IEEE 7th Symposium on Machine Learning for CAD Mlcad 2025
  published_on: '2025-09-08'
  doi: 10.1109/mlcad65511.2025.11189178
links:
  source: https://doi.org/10.1109/mlcad65511.2025.11189178
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

