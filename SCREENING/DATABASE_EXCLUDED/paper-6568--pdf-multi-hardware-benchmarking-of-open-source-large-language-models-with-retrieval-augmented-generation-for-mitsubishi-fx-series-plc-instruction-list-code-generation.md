---
schema: paper-monitor/paper/v1
paper_id: 6568
record_type: PAPER
bibliography:
  title: '[PDF] Multi-Hardware Benchmarking of Open-Source Large Language Models with Retrieval-Augmented Generation for Mitsubishi
    FX-Series PLC Instruction List Code Generation'
  authors: Ming‐Feng Yeh, Ching-Chuan Luo, Cheng-Lin Lu
  abstract: Smart manufacturing relies on programmable logic controllers (PLCs) that translate sensor inputs into actuator
    commands. Generating PLC programs in legacy textual languages such as Mitsubishi FX-series Instruction List (IL) remains
    an expert-only task, and IL's deprecation in IEC 61131-3 Edition 3.0 leaves it under-represented in the corpora that train
    modern large language models (LLMs). We benchmark ten open-source LLMs (five vendors, 7B-122B parameters) in both LLM-only
    and Retrieval-Augmented Generation (RAG) configurations on a frozen 285-question dataset; the pipeline uses ChromaDB with
    all-MiniLM-L6-v2 embeddings and Maximal Marginal Relevance (MMR) retrieval (k=3, λ=0.5). To move beyond lexical similarity
    we introduce a three-tier static syntax checker (Lexical/Syntactic/Semantic) calibrated against a 93.3% ground-truth pass
    rate. RAG raises the syntactic pass rate by +6.7 to +61.1 percentage points across all ten models; the best configuration,
    qwen3.5:122b with RAG, reaches 95.8%, exceeding the ground-truth baseline. Two outliers (llama3.3:70b at +6.7 pp, gpt-oss:120b
    at +25.6 pp) are reported rather than excluded. The results indicate that for deprecated-but-deployed industrial languages
    a curated dialect corpus paired with a locally-hosted open-source LLM is more effective than scaling raw model size, supporting
    reproducible, on-premise industrial-monitoring and code-generation tooling for sustainable smart manufacturing.
  publisher: Sensors.
  published_on: '2026-06-05'
  doi: 10.3390/s26113602
links:
  source: https://doi.org/10.3390/s26113602
  open_access: https://doi.org/10.3390/s26113602
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

