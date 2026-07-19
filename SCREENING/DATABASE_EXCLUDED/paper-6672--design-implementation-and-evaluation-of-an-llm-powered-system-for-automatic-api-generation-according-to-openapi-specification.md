---
schema: paper-monitor/paper/v1
paper_id: 6672
record_type: PAPER
bibliography:
  title: Design, Implementation, and Evaluation of an LLM-Powered System for Automatic API Generation According to OpenAPI
    Specification
  authors: Adnane Kesraoui, Omar Iraqi Houssaini, Asmaa Mourhir
  abstract: 'Large Language Models (LLMs) have become increasingly proficient in automating different software development
    tasks, particularly those that involve understanding natural language or generating code. However, the task of turning
    human-written Application Programming Interface (API) documentation into formal OpenAPI specifications remains largely
    underexplored. In this study, we investigate the use of LLMs to automatically generate OpenAPI 3.0.3 specifications from
    textual API documentation. To this end, we curated a benchmark dataset of approximately 1,600 publicly available API specifications
    in various domains. We then experimented on proprietary and open-source LLMs under different prompting and fine-tuning
    strategies. The results were captured using three adopted metrics: JSON and schema validity, and functional equivalence.
    Claude showed the strongest out-of-the-box performance, achieving the highest structural accuracy in a zero-shot scenario.
    GPT-4o-mini had the weakest JSON & schema validity, but ranked secondbest in extracting relevant endpoints and details
    at a decent cost, revealing a strong foundation for improvement through advanced prompting techniques (few-shot, chain-of-thought,
    and agentic prompting). Agentic prompting significantly improved structural accuracy but came with a notable increase
    in inference latency. In contrast, few-shot prompting slightly degraded performance, while chain-of-thought prompting
    offered only marginal improvements. We further fine-tuned the open-source Mistral-7B model using Low-Rank Adaptation (LoRA)
    under 4-bit quantization, which increased schema validity in in-distribution data, though it suffered a 30 % drop under
    longer-context drift. With access to more diverse and high-quality training data, this generalization gap could be mitigated.
    Our findings highlight trade-offs between different optimization strategies.'
  publisher: Sita 2025 15th International Conference on Intelligent Systems Theories and Applications
  published_on: '2025-10-20'
  doi: 10.1109/sita67914.2025.11273754
links:
  source: https://doi.org/10.1109/sita67914.2025.11273754
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

