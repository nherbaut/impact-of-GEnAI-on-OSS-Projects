---
schema: paper-monitor/paper/v1
paper_id: 6680
record_type: PAPER
bibliography:
  title: 'Towards Secure Code Generation With LLMs: A Study on Common Weakness Enumeration'
  authors: Jianguo Zhao, Yuqiang Sun, Cheng Huang, Chengwei Liu, YaoHui Guan, Yutong Zeng, Yang Liu
  abstract: Automated code generation has revolutionized software development, enabling developers to accelerate project timelines
    and reduce manual coding errors significantly. As reliance on these technologies grows, the inherent weaknesses of generated
    code become increasingly apparent. Recent studies have shown that code produced by AI is not inherently safer or of higher
    quality than human-written code, often replicating existing vulnerabilities. To this end, we propose SECURECODER, which
    integrates Retrieval-Augmented Generation (RAG) with Common Weakness Enumeration (CWE). SECURECODER first utilizes the
    advanced reasoning capabilities of large language models (LLMs) to generate natural language descriptions of the code’s
    core business logic and functionality. Then, from a semantic perspective, it matches the requirements of the code generation
    task with the CWE descriptions through a multi-label classification process. Finally, based on the matched CWE, SECURECODER
    generates a list of security guidelines the code generation model must adhere to. Breaking down end-to-end code generation
    tasks into single-target tasks that LLMs excel at ensures that the generated code not only meets functional requirements
    but also adheres to best security practices, thereby enhancing the interpretability of the automated code generation process.
    After evaluating 2 programming languages and 7 LLMs on Coploit-generated code, SECURECODER has great generalization capability
    and could be applied to more programming languages and vulnerability types. SECURECODER could significantly decrease the
    security weakness in the AI-generated code and is able to mitigate more than 65% of vulnerabilities exposed to software
    developers. Compared to the baseline open-source LLMs, code vulnerabilities were reduced by at least 14% and the code
    business logic was not affected.
  publisher: IEEE Transactions on Software Engineering
  published_on: '2025-10-09'
  doi: 10.1109/tse.2025.3619281
links:
  source: https://doi.org/10.1109/tse.2025.3619281
  open_access: null
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-06-30T13:29:23.865282Z'
workflow:
  state:
    id: RETRIEVAL/DATABASE_SOUGHT_FOR_RETRIEVAL
    label: Database sought for retrieval
    prisma_bucket: DATABASE_SOUGHT_FOR_RETRIEVAL
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

