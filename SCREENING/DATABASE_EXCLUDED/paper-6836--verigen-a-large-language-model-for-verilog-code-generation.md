---
schema: paper-monitor/paper/v1
paper_id: 6836
record_type: PAPER
bibliography:
  title: 'VeriGen: A Large Language Model for Verilog Code Generation'
  authors: Shailja Thakur, Baleegh Ahmad, Hammond Pearce, Benjamin Tan, Brendan Dolan-Gavitt, Ramesh Karri, Siddharth Garg
  abstract: In this study, we explore the capability of Large Language Models (LLMs) to automate hardware design by automatically
    completing partial Verilog code, a common language for designing and modeling digital systems. We fine-tune pre-existing
    LLMs on Verilog datasets compiled from GitHub and Verilog textbooks. We evaluate the functional correctness of the generated
    Verilog code using a specially designed test suite, featuring a custom problem set and testing benches. Here, our fine-tuned
    open-source CodeGen-16B model outperforms the commercial state-of-the-art GPT-3.5-turbo model with a 1.1% overall increase.
    Upon testing with a more diverse and complex problem set, we find that the fine-tuned model shows competitive performance
    against state-of-the-art gpt-3.5-turbo, excelling in certain scenarios. Notably, it demonstrates a 41% improvement in
    generating syntactically correct Verilog code across various problem categories compared to its pre-trained counterpart,
    highlighting the potential of smaller, in-house LLMs in hardware design automation. We release our training/evaluation
    scripts and LLM checkpoints as open-source contributions.
  publisher: ACM Transactions on Design Automation of Electronic Systems
  published_on: '2024-02-09'
  doi: 10.1145/3643681
links:
  source: https://doi.org/10.1145/3643681
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

