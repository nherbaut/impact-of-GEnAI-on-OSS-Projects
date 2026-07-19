---
schema: paper-monitor/paper/v1
paper_id: 6813
record_type: PAPER
bibliography:
  title: '[PDF] LiCoEval: Evaluating LLMs on License Compliance in Code Generation'
  authors: Weiwei Xu, Kai Gao, Hao He, Minghui Zhou
  abstract: Recent advances in Large Language Models (LLMs) have revolutionized code generation, leading to widespread adoption
    of AI coding tools by developers. However, LLMs can generate license-protected code without providing the necessary license
    information, leading to potential intellectual property violations during software production. This paper addresses the
    critical, yet underexplored, issue of license compliance in LLM-generated code by establishing a benchmark to evaluate
    the ability of LLMs to provide accurate license information for their generated code. To establish this benchmark, we
    conduct an empirical study to identify a reasonable standard for "striking similarity" that excludes the possibility of
    independent creation, indicating a copy relationship between the LLM output and certain open-source code. Based on this
    standard, we propose LiCoEval, to evaluate the license compliance capabilities of LLMs, i.e., the ability to provide accurate
    license or copyright information when they generate code with striking similarity to already existing copyrighted code.
    Using LiCoEval, we evaluate 14 popular LLMs, finding that even top-performing LLMs produce a non-negligible proportion
    (0.88% to 2.01%) of code strikingly similar to existing open-source implementations. Notably, most LLMs fail to provide
    accurate license information, particularly for code under copyleft licenses. These findings underscore the urgent need
    to enhance LLM compliance capabilities in code generation tasks. Our study provides a foundation for future research and
    development to improve license compliance in AI-assisted software development, contributing to both the protection of
    open-source software copyrights and the mitigation of legal risks for LLM users.
  publisher: arXiv.org.
  published_on: '2024-08-05'
  doi: null
links:
  source: http://arxiv.org/abs/2408.02487v3
  open_access: https://arxiv.org/abs/2408.02487v3
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

