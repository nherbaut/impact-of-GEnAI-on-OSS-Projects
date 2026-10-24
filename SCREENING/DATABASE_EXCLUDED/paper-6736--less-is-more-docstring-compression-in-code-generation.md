---
schema: paper-monitor/paper/v1
paper_id: 6736
record_type: PAPER
bibliography:
  title: 'Less Is More: DocString Compression in Code Generation'
  authors: Guang Yang, Yu Zhou, Wei Cheng, Xiangyu Zhang, Xiang Chen, Terry Yue Zhuo, Ke Liu, Xin Zhou, David Lo, Taolue Chen
  abstract: The widespread use of Large Language Models (LLMs) in software engineering has intensified the need for improved
    model and resource efficiency. In particular, for neural code generation, LLMs are used to translate function/method signature
    and DocString to executable code. DocStrings, which capture user requirements for the code and are typically used as the
    prompt for LLMs, often contain redundant information. Recent advancements in prompt compression have shown promising results
    in Natural Language Processing (NLP), but their applicability to code generation remains uncertain. Our empirical study
    shows that the state-of-the-art prompt compression methods achieve only about 10% reduction, as further reductions would
    cause significant performance degradation. In our study, we propose a novel compression method, ShortenDoc, dedicated
    to DocString compression for code generation. Our experiments on six code generation datasets, five open source LLMs (1B
    to 10B parameters), and one closed-source LLM GPT-4o confirm that ShortenDoc achieves 25–40% compression while preserving
    the quality of generated code, outperforming other baseline methods at similar compression levels. The benefit of this
    method is to improve efficiency and reduce the token processing cost while maintaining the quality of the generated code,
    especially when calling third-party APIs.
  publisher: ACM Transactions on Software Engineering and Methodology
  published_on: '2025-05-14'
  doi: 10.1145/3735636
links:
  source: https://doi.org/10.1145/3735636
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

