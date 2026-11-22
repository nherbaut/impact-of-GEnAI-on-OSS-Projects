---
schema: paper-monitor/paper/v1
paper_id: 15541
record_type: PAPER
bibliography:
  title: '[PDF] Bigger Is Not Always Better: Performance and Sustainability Trade-Offs in LLMs for Python Bug-Fixing Tasks'
  authors: Syed Fakhar Abbas Naqvi, Hina Anwar
  abstract: Background. Large Language Models (LLMs) are increasingly used in software engineering tasks such as code generation,
    bug detection, and program repair. However, their use introduces inference-time costs that are rarely considered together
    with functional performance, especially in debugging and repair workflows where models may be invoked repeatedly. Aim.
    This study evaluates the correctness-energy trade-offs of LLMs across model scales in Python bug-fixing tasks. We examine
    how model size relates to code correctness, inference time, and GPU energy consumption. Method. We conduct a controlled
    empirical evaluation of six open-source code-oriented LLMs, ranging from 1.5B to 15B parameters, on 40 real-world Python
    bugs from the BugsInPy benchmark. Each model is executed multiple times per task under a consistent hardware and prompting
    setup. Repair performance is measured using Pass@k and test-suite outcomes, while computational cost is measured using
    inference time and GPU energy consumption. We also analyze generated outputs to identify recurring failure patterns. Results.
    Increasing model size substantially raised computational cost without consistently improving correctness. The smallest
    model, Qwen 1.5B, achieved the best overall performance, with a Pass@1 score of 43% and an average runtime of 38.7 seconds.
    In contrast, StarCoder 15B achieved a Pass@1 score of 23%, required 96.7 seconds, and consumed approximately 7 times more
    energy per inference while solving fewer tasks. Higher success rates were also observed in web-related projects, suggesting
    that structurally localized bugs are more effectively handled by current models. Conclusion. On the evaluated localized
    Python bug-fixing tasks, smaller LLMs offered a more favorable trade-off between correctness, inference time, and energy
    consumption. These results suggest that scaling model size does not automatically lead to more efficient LLM-based repair,
    and that inference cost should be considered alongside functional correctness when comparing models.
  publisher: Leibniz International Proceedings in Informatics Lipics.
  published_on: '2026-01-01'
  doi: 10.4230/lipics.esem.2026.34
links:
  source: https://doi.org/10.4230/lipics.esem.2026.34
  open_access: https://drops.dagstuhl.de/storage/00lipics/lipics-vol394-esem2026/LIPIcs.ESEM.2026.34/LIPIcs.ESEM.2026.34.pdf
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-11-07T07:27:35.004833Z'
workflow:
  state:
    id: IDENTIFICATION/DATABASE_IDENTIFIED
    label: Database identified
    prisma_bucket: DATABASE_IDENTIFIED
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

