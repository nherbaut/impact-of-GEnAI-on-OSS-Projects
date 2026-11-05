---
schema: paper-monitor/paper/v1
paper_id: 6708
record_type: PAPER
bibliography:
  title: Empirical Evaluation of LLMs for Automated Program Fault Localisation
  authors: Yong Liu, Xin Wang, Hengyuan Liu, R. Stephanie Huang, Yonghao Wu
  abstract: Many recent service interruptions caused by software faults have shown that fault localisation is crucial for
    automated debugging and repair. In this context, Large Language Models (LLMs) have emerged as a promising tool that has
    demonstrated strong capabilities in a variety of software engineering tasks such as code generation, program repair, summarisation
    and test generation. While existing research has either leveraged LLMs for function-level fault localisation or fine-tuned
    them using exclusively faulty code snippets, the efficacy of LLM-based statement-level fault localisation with dynamic
    execution information remains inadequately investigated. Therefore, to address this research gap, we present a comprehensive
    empirical evaluation of statement-level fault localisation capabilities across multiple LLM architectures, including the
    ChatGPT series, the DeepSeek series, and small-scale, locally deployed open-source language models. Utilising the extensively
    validated Defects4J v1.5.0 benchmark, we systematically compare these models against existing statement-level fault localisation
    techniques. We also investigate the consistency of LLMs in fault localisation, as well as how prompt engineering affects
    the fault localisation effectiveness. Our empirical findings reveal that within a function-level context, DeepSeek-R1
    surpasses all baselines in statement-level fault localisation, with the integration of error logs enhancing accuracy by
    72.6% over SmartFL in terms of TOP-1 metric. Moreover, our ablation experiments demonstrate that removing test cases and
    error logs reduces the LLM’s TOP-1 accuracy by 4.7% and 8.6% on average, respectively, while explicit instructions to
    rank faulty statements improves accuracy by 6.9%. These observations suggest that LLMs offer promising capabilities for
    automated fault localisation. Furthermore, utilising dynamic execution information and providing instructions to rank
    faulty statements can significantly enhance the fault localisation capabilities of LLMs.
  publisher: Proceedings 2025 25th International Conference on Software Quality Reliability and Security Companion Qrs C 2025
  published_on: '2025-07-16'
  doi: 10.1109/qrs-c65679.2025.00063
links:
  source: https://doi.org/10.1109/qrs-c65679.2025.00063
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

