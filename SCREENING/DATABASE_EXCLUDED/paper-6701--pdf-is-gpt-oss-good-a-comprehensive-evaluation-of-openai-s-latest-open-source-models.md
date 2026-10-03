---
schema: paper-monitor/paper/v1
paper_id: 6701
record_type: PAPER
bibliography:
  title: '[PDF] Is GPT-OSS Good? A Comprehensive Evaluation of OpenAI''s Latest Open Source Models'
  authors: Ziqian Bi, Keyu Chen, Chiung-Yi Tseng, Danyang Zhang, Tianyang Wang, Hongying Luo, Lu Chen, Junming Huang, Jibin
    Guan, Junfeng Hao, Xinyuan Song, Junhao Song
  abstract: In August 2025, OpenAI released GPT-OSS models, its first open weight large language models since GPT-2 in 2019,
    comprising two mixture of experts architectures with 120B and 20B parameters. We evaluated both variants against six contemporary
    open source large language models ranging from 14.7B to 235B parameters, representing both dense and sparse designs, across
    ten benchmarks covering general knowledge, mathematical reasoning, code generation, multilingual understanding, and conversational
    ability. All models were tested in unquantised form under standardised inference settings, with statistical validation
    using McNemars test and effect size analysis. Results show that gpt-oss-20B consistently outperforms gpt-oss-120B on several
    benchmarks, such as HumanEval and MMLU, despite requiring substantially less memory and energy per response. Both models
    demonstrate mid-tier overall performance within the current open source landscape, with relative strength in code generation
    and notable weaknesses in multilingual tasks. These findings provide empirical evidence that scaling in sparse architectures
    may not yield proportional performance gains, underscoring the need for further investigation into optimisation strategies
    and informing more efficient model selection for future open source deployments. More details and evaluation scripts are
    available at https://ai-agent-lab.github.io/gpt-oss (Project Webpage).
  publisher: arXiv.org.
  published_on: '2025-08-17'
  doi: null
links:
  source: http://arxiv.org/abs/2508.12461v3
  open_access: https://arxiv.org/abs/2508.12461v3
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
  tags:
  - arxiv
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

