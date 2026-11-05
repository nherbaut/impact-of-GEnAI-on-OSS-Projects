---
schema: paper-monitor/paper/v1
paper_id: 14615
record_type: PAPER
bibliography:
  title: '[PDF] SCCGBench: Executability-Oriented Evaluation for Real-World Web Service-Call Code Generation'
  authors: Shuo Wang, Guodong Fan, Ming Zhu, Jing Li, Chun Wang
  abstract: 'LLM-generated service-call code is increasingly important for service computing, where developers rely on large
    language models (LLMs) to compose services and invoke third-party services. However, current approaches have not yet evaluated
    the invocation and execution of services in the actual code environment. To support execution-grounded evaluation, we
    present the Service-Call Code Generation Benchmark (SCCGBench), a benchmark of 3,135 traceable and decontamination-filtered
    RapidAPI call functions from real GitHub repositories. SCCGBench uses redacted-intent generation to reduce circular leakage
    and introduces Mock, Robust, ParamF1, and host-, endpoint-, method-, and parameter-level diagnostics. Mock denotes a virtual-execution
    hit that simultaneously matches the gold host, endpoint, and HTTP method, while Robust further requires status checking
    and exception handling. We evaluate six code LLMs and one non-neural retrieval baseline under intent-only, retrieval-augmented,
    and gold-documentation Oracle settings. Results show that models often generate syntactically correct or superficially
    similar HTTP-request code but achieve low Mock success in the intent-only setting; the strongest evaluated model obtains
    only 3.76% Mock. Under the gold-documentation Oracle settings (C3 and C5), Mock reaches 88.73%--90.52% for the open-source
    models evaluated in RQ2 and 76.47%--81.86% for DeepSeek-V4-Pro, whereas sparse and dense retrieval remain far below this
    oracle level. The findings indicate that service/API grounding is the main bottleneck: Mock is dominated by host, endpoint,
    and method alignment, while ParamF1 separately reveals parameter-alignment errors. SCCGBench provides an execution-grounded
    benchmark for Web service invocation, API recommendation, service-interface retrieval, endpoint grounding, and reliable
    service-call automation.'
  publisher: arXiv.org.
  published_on: '2026-10-09'
  doi: null
links:
  source: http://arxiv.org/abs/2610.12920v1
  open_access: https://arxiv.org/abs/2610.12920v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-12T05:10:22.005512Z'
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

