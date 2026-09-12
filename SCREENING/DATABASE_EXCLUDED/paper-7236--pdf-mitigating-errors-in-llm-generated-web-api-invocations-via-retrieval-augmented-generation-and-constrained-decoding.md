---
schema: paper-monitor/paper/v1
paper_id: 7236
record_type: PAPER
bibliography:
  title: '[PDF] Mitigating Errors in LLM-Generated Web API Invocations via Retrieval-Augmented Generation and Constrained
    Decoding'
  authors: Daniel Maninger, Leon Chemnitz, Jannis Brugger, Tushar Lamba, Amir Molzam Sharifloo, Mira Mezini
  abstract: Integration of web APIs is a cornerstone of modern software systems, yet writing correct web API invocation code
    remains challenging due to complex and evolving API specifications. Although LLMs are increasingly used for code generation,
    previous work has empirically shown that their ability to generate correct web API integrations is limited. At the same
    time, mitigation techniques and their effectiveness for this setting remain insufficiently understood. In this paper,
    we propose and systematically evaluate retrieval-augmented generation (RAG) and constrained decoding (CD) as two complementary
    approaches to improving LLM-generated web API invocation code. For RAG, we design a retriever that processes OpenAPI specifications
    and retrieves compact endpoint representations to inject into model prompts. For CD, we introduce an automatic translation
    from OpenAPI specifications to regex-based constraints enforced during generation. We evaluate both approaches on WAPIIBench's
    existing synthetic dataset and on a new real-world dataset derived from GitHub repositories. Our results show that RAG
    reduces hallucinations and improves correctness when generating full API invocations but reduces it when the endpoint
    is already provided as it encourages the generation of unnecessary parameters. In contrast, CD reliably prevents illegal
    URLs, HTTP methods, and arguments and substantially improves overall correctness for both starter codes.
  publisher: arXiv.org.
  published_on: '2026-07-07'
  doi: null
links:
  source: http://arxiv.org/abs/2607.05936v1
  open_access: https://arxiv.org/abs/2607.05936v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-07-08T11:41:21.235128Z'
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

