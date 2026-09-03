---
schema: paper-monitor/paper/v1
paper_id: 6709
record_type: PAPER
bibliography:
  title: '[PDF] NLPerturbator: Studying the Robustness of Code LLMs to Natural Language Variations'
  authors: Junkai Chen, Zhenhao Li, Xing Hu, Xin Xia
  abstract: Large language models achieve promising results in code generation based on a given natural language description.
    They have been integrated into open source projects and commercial products to facilitate daily coding activities. The
    natural language description in the prompt is crucial for LLMs to comprehend users’ requirements. Prior studies have uncovered
    that LLMs are sensitive to changes in the prompts, including slight changes that look inconspicuous. However, the natural
    language descriptions often vary in real-world scenarios (e.g., different formats, grammar, and wording). Prior studies
    on the robustness of LLMs were often based on random perturbations, and such perturbations may not actually happen. In
    this article, we conduct a comprehensive study to investigate how code LLMs are robust to variations of natural language
    descriptions in real-world scenarios. We summarize 18 categories of perturbations of natural language and three combinations
    of co-occurred categories based on our literature review and online survey with practitioners. We propose an automated
    framework, NLPerturbator, which can perform perturbations of each category given a set of prompts. Through a series of
    experiments on code generation using sevencode LLMs, we find that the perturbed prompts can decrease the performance of
    code generation by a considerable margin. Our study highlights the importance of enhancing the robustness of LLMs to real-world
    variations in the prompts, as well as the essentiality of attentively constructing the prompts.
  publisher: ACM Transactions on Software Engineering and Methodology.
  published_on: '2025-07-08'
  doi: 10.1145/3745764
links:
  source: https://doi.org/10.1145/3745764
  open_access: https://arxiv.org/abs/2406.19783v1
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

