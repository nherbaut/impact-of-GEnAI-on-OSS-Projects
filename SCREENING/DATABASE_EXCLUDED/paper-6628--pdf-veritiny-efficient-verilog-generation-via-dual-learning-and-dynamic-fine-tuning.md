---
schema: paper-monitor/paper/v1
paper_id: 6628
record_type: PAPER
bibliography:
  title: '[PDF] VeriTiny: Efficient Verilog Generation via Dual Learning and Dynamic Fine-Tuning'
  authors: Shuaifeng Huang, Lijuan Tang, Y Wang, Guang Yang
  abstract: 'Automatic Verilog code generation based on large language models has emerged as a critical research direction
    in Electronic Design Automation (EDA). However, existing methods face two core challenges: (1) data scarcity, Verilog
    domain datasets are extremely limited, with current approaches either mining noisy open-source code from GitHub or synthesizing
    data via LLMs with uncontrollable quality and potential copyright issues; (2) model efficiency, high-performance models
    require billions of parameters, making them unsuitable for resource-constrained environments. To address these challenges,
    we focus on enabling effective model learning from limited labeled samples. We propose VeriTiny, a lightweight Verilog
    code generation model with 0.6B parameters, featuring two key components: (1) dual task learning with unidirectional pseudo-sample
    augmentation (PSA), where the reverse model generates pseudo-descriptions for real Verilog code to expand limited training
    data, while intentionally excluding the opposite augmentation direction to avoid noise from model-generated code; (2)
    Dynamic Fine-Tuning (DFT) that scales each token’s cross-entropy loss by its predicted probability, suppressing gradient
    variance and enabling more stable learning from scarce data. Furthermore, through continual pre-training on hardware domain-specific
    corpora to enhance Verilog syntax understanding, and a syntax-first selection mechanism to prioritize syntactically correct
    code, our approach significantly improves performance. Experimental results demonstrate that VeriTiny achieves 76.85%
    syntax correctness and 34.02% functional correctness on average, significantly outperforming baseline 0.6B models while
    matching mainstream 7B models in syntax correctness and approaching them in functional correctness, with only 10% of their
    parameters, substantially lower deployment cost, and competitive end-to-end local inference.'
  publisher: IEEE Access.
  published_on: '2026-01-01'
  doi: 10.1109/access.2026.3693001
links:
  source: https://doi.org/10.1109/access.2026.3693001
  open_access: https://doi.org/10.1109/access.2026.3693001
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

