---
schema: paper-monitor/paper/v1
paper_id: 6858
record_type: PAPER
bibliography:
  title: '[PDF] LLMSecEval: A Dataset of Natural Language Prompts for Security Evaluations'
  authors: Catherine Tony, Markus Mutas, Nicolás E. Díaz Ferreyra, Riccardo Scandariato
  abstract: Large Language Models (LLMs) like Codex are powerful tools for performing code completion and code generation
    tasks as they are trained on billions of lines of code from publicly available sources. Moreover, these models are capable
    of generating code snippets from Natural Language (NL) descriptions by learning languages and programming practices from
    public GitHub repositories. Although LLMs promise an effortless NL-driven deployment of software applications, the security
    of the code they generate has not been extensively investigated nor documented. In this work, we present LLMSecEval, a
    dataset containing 150 NL prompts that can be leveraged for assessing the security performance of such models. Such prompts
    are NL descriptions of code snippets prone to various security vulnerabilities listed in MITRE’s Top 25 Common Weakness
    Enumeration (CWE) ranking. Each prompt in our dataset comes with a secure implementation example to facilitate comparative
    evaluations against code produced by LLMs. As a practical application, we show how LLMSecEval can be used for evaluating
    the security of snippets automatically generated from NL descriptions.
  publisher: Proceedings 2023 IEEE ACM 20th International Conference on Mining Software Repositories MSR 2023.
  published_on: '2023-05-01'
  doi: 10.1109/msr59073.2023.00084
links:
  source: https://doi.org/10.1109/msr59073.2023.00084
  open_access: https://arxiv.org/abs/2303.09384v1
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

