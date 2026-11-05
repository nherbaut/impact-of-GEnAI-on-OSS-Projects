---
schema: paper-monitor/paper/v1
paper_id: 7420
record_type: PAPER
bibliography:
  title: '[PDF] RIDGE: An Autonomous Framework for Validation and Method Discovery in LLM-Generated Option Pricing'
  authors: Liexin Cheng, Xue Cheng, Shuaiqiang Liu, Cornelis W. Oosterlee
  abstract: 'Automated code generation is becoming an important tool in quantitative finance, where large language models
    can generate option pricing implementations directly from mathematical model specifications. Validating such implementations,
    however, requires considerably more than conventional software testing: numerical pricing methods must remain mathematically
    consistent, numerically stable, and reliable across a wide range of model parameters. We introduce RIDGE, an autonomous
    validation framework in which generated pricing implementations are subjected to structured no-arbitrage tests, stress
    tests, benchmark comparisons, and consistency checks. Validation evidence is interpreted diagnostically, while the resulting
    knowledge is accumulated in a repository and reused across models and successive validation iterations. This enables systematic
    refinement of both the pricing implementation and the validation methodology. The framework is applied to five stochastic
    volatility models. Across these studies, all detected implementation defects are removed and, in two cases, the validation
    process reveals methodological limitations and motivates the development of alternative numerical methods. The supplementary
    material is available in the GitHub repository: https://github.com/ShQiangLiu/ridge.'
  publisher: arXiv.org.
  published_on: '2026-07-28'
  doi: null
links:
  source: http://arxiv.org/abs/2607.25199v2
  open_access: https://arxiv.org/abs/2607.25199v2
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-08-01T01:06:13.779804Z'
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

