---
schema: paper-monitor/paper/v1
paper_id: 6808
record_type: PAPER
bibliography:
  title: '[PDF] Automated C/C++ Program Repair for High-Level Synthesis via Large Language Models'
  authors: Kangwei Xu, Grace Li Zhang, Xunzhao Yin, Cheng Zhuo, Ulf Schlichtmann, Bing Li
  abstract: 'In High-Level Synthesis (HLS), converting a regular C/C++ program into its HLS-compatible counterpart (HLS-C)
    still requires tremendous manual effort. Various program scripts have been introduced to automate this process. But the
    resulting codes usually contain many issues that should be manually repaired by developers. Since Large Language Models
    (LLMs) have the ability to automate code generation, they can also be used for automated program repair in HLS. However,
    due to the limited training of LLMs considering hardware and software simultaneously, hallucinations may occur during
    program repair using LLMs, leading to compilation failures. Besides, using LLMs for iterative repair also incurs a high
    cost. To address these challenges, we propose an LLM-driven program repair framework that takes regular C/C++ code as
    input and automatically generates its corresponding HLS-C code for synthesis while minimizing human repair effort. To
    mitigate the hallucinations in LLMs and enhance the prompt quality, a Retrieval-Augmented Generation (RAG) paradigm is
    introduced to guide the LLMs toward correct repair. In addition, we use LLMs to create a static bit width optimization
    program to identify the optimized bit widths for variables. Moreover, LLM-driven HLS optimization strategies are introduced
    to add/tune pragmas in HLS-C programs for circuit optimization. Experimental results demonstrate that the proposed LLM-driven
    automated framework can achieve much higher repair pass rates in 24 real-world applications compared with the traditional
    scripts and the direct application of LLMs for program repair. The codes are open-sourced at this link: https://github.com/code-source1/catapult.'
  publisher: Mlcad 2024 Proceedings of the 2024 ACM IEEE International Symposium on Machine Learning for CAD.
  published_on: '2024-09-03'
  doi: 10.1145/3670474.3685953
links:
  source: https://doi.org/10.1145/3670474.3685953
  open_access: https://doi.org/10.1145/3670474.3685953
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

