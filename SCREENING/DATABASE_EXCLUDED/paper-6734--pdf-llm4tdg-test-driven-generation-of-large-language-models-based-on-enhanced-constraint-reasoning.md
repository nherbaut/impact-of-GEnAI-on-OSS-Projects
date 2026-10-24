---
schema: paper-monitor/paper/v1
paper_id: 6734
record_type: PAPER
bibliography:
  title: '[PDF] LLM4TDG: test-driven generation of large language models based on enhanced constraint reasoning'
  authors: Jingqiang Liu, Ruigang Liang, Xinran Zhu, Yue Zhang, Yuling Liu, Qixu Liu
  abstract: Abstract With the evolution of modern software development paradigms, component reuse, and low-code approaches
    have emerged as mainstream in software development. However, developers often lack an in-depth understanding of reused
    code. The inability of components to operate autonomously leads to insufficient testing of software functionalities and
    security, further exacerbating the contradiction between the increasing complexity of software architectures and the demand
    for accurate and efficient software automation testing. This, in turn, increases the frequency of software supply chain
    security incidents. This paper proposes a test-driven generation framework, LLM4TDG, based on large language models (LLMs).
    By formally defining the constraint dependency graph and converting it into context constraints, LLMs’ ability to understand
    natural language descriptions such as test requirements and documents is enhanced. Constraint reasoning and backtracking
    mechanisms are then used to generate test drivers that satisfy the defined constraints automatically. Using the EvalPlus
    dataset, we evaluate the comprehensive capabilities of LLM4TDG in test case generation using four general-domain LLMs
    and five code-generation-domain LLMs. The experimental results indicate that our approach significantly enhances LLMs’
    ability to comprehend constraints in testing objectives, achieving a 47.62% increase in constraint understanding across
    147 testing tasks. Employing LLM4TDG significantly improves the average pass@k metric of all LLMs by 10.41%. The pass@k
    metric for CodeQwen-chat has improved by up to 18.66%. The metric surpasses the state-of-the-art GPT-4, with a performance
    of 92.16% on HUMANEVAL and 87.14% on HUMANEVAL+, which enhances the error correction and functional correctness in test-driven
    code generation. Meanwhile, Our experiments were conducted on a dataset of Python third-party libraries containing malicious
    behavior in the context of security testing tasks, validating the effectiveness of our method in real-world applications
    and its generalization capabilities.
  publisher: Cybersecurity.
  published_on: '2025-05-15'
  doi: 10.1186/s42400-024-00335-4
links:
  source: https://doi.org/10.1186/s42400-024-00335-4
  open_access: https://cybersecurity.springeropen.com/counter/pdf/10.1186/s42400-024-00335-4
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

