---
schema: paper-monitor/paper/v1
paper_id: 6604
record_type: PAPER
bibliography:
  title: '[PDF] Agentic RAG for Maritime AIoT: Natural Language Access to Structured Data'
  authors: Oxana Sachenkova, Melker Andreasson, Dongzhu Tan, Alisa Lincke
  abstract: 'Maritime operations are increasingly reliant on sensor data to drive efficiency and enhance decision-making.
    However, despite rapid advances in large language models, including expanded context windows and stronger generative capabilities,
    critical industrial settings still require secure, role-constrained access to enterprise data and explicit limitation
    of model context. Retrieval-Augmented Generation (RAG) remains essential to enforce data minimization, preserve privacy,
    support verifiability, and meet regulatory obligations by retrieving only permissioned, provenance-tracked slices of information
    at query time. However, current RAG solutions lack robust validation protocols for numerical accuracy for high-stakes
    industrial applications. This paper introduces Lighthouse Bot, a novel Agentic RAG system specifically designed to provide
    natural-language access to complex maritime sensor data, including time-series and relational sensor data. The system
    addresses a critical need for verifiable autonomous data analysis within the Artificial Intelligence of Things (AIoT)
    domain, which we explore through a case study on optimizing ferry operations. We present a detailed architecture that
    integrates a Large Language Model with a specialized database and coding agents to transform natural language into executable
    tasks, enabling core AIoT capabilities such as generating Python code for time-series analysis, executing complex SQL
    queries on relational sensor databases, and automating workflows, while keeping sensitive data outside the prompt and
    ensuring auditable, policy-aligned tool use. To evaluate performance, we designed a test suite of 24 questions with ground-truth
    answers, categorized by query complexity (simple, moderate, complex) and data interaction type (retrieval, aggregation,
    analysis). Our results show robust, controlled data access with high factual fidelity: the proprietary Claude 3.7 achieved
    close to 90% overall factual correctness, while the open-source Qwen 72B achieved 66% overall and 99% on simple retrieval
    and aggregation queries. These findings underscore the need for a secure limited-context RAG in maritime AIoT and the
    potential for cost-effective automation of routine exploratory analyses.'
  publisher: Sensors.
  published_on: '2026-02-13'
  doi: 10.3390/s26041227
links:
  source: https://doi.org/10.3390/s26041227
  open_access: https://www.mdpi.com/1424-8220/26/4/1227/pdf?version=1770986151
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

