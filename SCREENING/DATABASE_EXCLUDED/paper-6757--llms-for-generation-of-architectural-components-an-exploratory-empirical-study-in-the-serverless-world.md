---
schema: paper-monitor/paper/v1
paper_id: 6757
record_type: PAPER
bibliography:
  title: 'LLMs for Generation of Architectural Components: An Exploratory Empirical Study in the Serverless World'
  authors: Shrikara Arun, Meghana Tedla, Karthik Vaidhyanathan
  abstract: Recently, the exponential growth in capability and pervasiveness of Large Language Models (LLMs) has led to significant
    work done in the field of code generation. However, this generation has been limited to code snippets. Going one step
    further, our desideratum is to automatically generate architectural components. This would not only speed up development
    time, but would also enable us to eventually completely skip the development phase, moving directly from design decisions
    to deployment. To this end, we conduct an exploratory study on the capability of LLMs to generate architectural components
    for Functions as a Service (FaaS), commonly known as serverless functions. The small size of their architectural components
    make this architectural style amenable for generation using current LLMs compared to other styles like monoliths and microservices.
    We perform the study by systematically selecting open source serverless repositories, masking a serverless function and
    utilizing state of the art LLMs provided with varying levels of context information about the overall system to generate
    the masked function. We evaluate correctness through existing tests present in the repositories and use metrics from the
    Software Engineering (SE) and Natural Language Processing (NLP) domains to evaluate code quality and the degree of similarity
    between human and LLM generated code respectively. Along with our findings, we also present a discussion on the path forward
    for using GenAI in architectural component generation.
  publisher: Proceedings 2025 IEEE 22nd International Conference on Software Architecture Icsa 2025
  published_on: '2025-03-31'
  doi: 10.1109/icsa65012.2025.00013
links:
  source: https://doi.org/10.1109/icsa65012.2025.00013
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

