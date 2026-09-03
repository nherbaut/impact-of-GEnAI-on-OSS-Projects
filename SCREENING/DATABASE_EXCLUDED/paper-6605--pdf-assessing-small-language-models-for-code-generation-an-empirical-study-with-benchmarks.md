---
schema: paper-monitor/paper/v1
paper_id: 6605
record_type: PAPER
bibliography:
  title: '[PDF] Assessing small language models for code generation: An empirical study with benchmarks'
  authors: Md Mahade Hasan, Muhammad Waseem, Kai‐Kristian Kemell, Jussi Rasku, Juha Ala-Rantala, Pekka Abrahamsson
  abstract: 'The recent advancements of Small Language Models (SLMs) have opened new possibilities for efficient code generation.
    SLMs offer lightweight and cost-effective alternatives to Large Language Models (LLMs), making them attractive for use
    in resource-constrained environments. However, empirical understanding of SLMs, particularly their capabilities, limitations,
    and performance trade-offs in code generation remains limited. This study presents a comprehensive empirical evaluation
    of 20 open-source SLMs ranging from 0.4B to 10B parameters on five diverse code-related benchmarks (HumanEval, MBPP, Mercury,
    HumanEvalPack, and CodeXGLUE). The models are assessed along three dimensions: i) functional correctness of generated
    code, ii) computational efficiency and iii) performance across multiple programming languages. The findings of this study
    reveal that several compact SLMs achieve competitive results while maintaining a balance between performance and efficiency,
    making them viable for deployment in resource-constrained environments. However, achieving further improvements in accuracy
    requires switching to larger models. These models generally outperform their smaller counterparts, but they require much
    more computational power. We observe that for 10% performance improvements, models can require nearly a 4x increase in
    VRAM consumption, highlighting a trade-off between effectiveness and scalability. Besides, the multilingual performance
    analysis reveals that SLMs tend to perform better in languages such as Python, Java, and PHP, while exhibiting relatively
    weaker performance in Go, C++, and Ruby. However, statistical analysis suggests these differences are not significant,
    indicating a generalizability of SLMs across programming languages. Based on the findings, this work provides insights
    into the design and selection of SLMs for real-world code generation tasks.'
  publisher: Journal of Systems and Software.
  published_on: '2026-02-13'
  doi: 10.1016/j.jss.2026.112815
links:
  source: https://doi.org/10.1016/j.jss.2026.112815
  open_access: https://doi.org/10.1016/j.jss.2026.112815
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

