---
schema: paper-monitor/paper/v1
paper_id: 7279
record_type: PAPER
bibliography:
  title: '[PDF] From Codebases to LLMs: Non-Inclusive Naming in Linux Foundation Repositories'
  authors: Honghao Tan, Md Nafiu Rahman, Shin Hwei Tan
  abstract: 'Since 2020, the Linux Foundation and the multi-organization Inclusive Naming Initiative (INI) have encouraged
    open-source projects to replace non-inclusive terms such as master/slave and whitelist/blacklist. Although these recommendations
    have been widely adopted, there is limited empirical evidence on their long-term adoption across Linux Foundation (LF)
    projects or their implications for AI-assisted software development. In this paper, we present NISCAN, a multilingual
    static-analysis framework that detects non-inclusive terminology across source code and related software artifacts using
    the INI vocabulary. Using NISCAN, we conduct the first ecosystem-scale study of inclusive naming across 461 Linux Foundation
    repositories. Our analysis shows that non-inclusive terminology has declined by approximately 47% since 2020, yet adoption
    remains incomplete: 62.7% of repositories still contain at least one Tier-1 non-inclusive identifier, while most remaining
    terminology resides outside source code in documentation, comments, configuration files, and other software artifacts.
    We further show that repository size, programming language, project functionality, and ecosystem are stronger predictors
    of term inclusiveness in LF repositories rather than foundation governance. To examine the implications for AI-assisted
    software development, we conduct a case study evaluating whether large language models (LLMs) can reconstruct legacy non-inclusive
    identifiers from surrounding program context. The results show that historical naming decisions remain embedded in model
    predictions even after identifiers have been renamed. Overall, our study findings provide the first ecosystem-scale assessment
    of inclusive naming adoption within the Linux Foundation and highlight the importance of addressing terminology residue
    to support responsible naming and ethically sourced code generation.'
  publisher: arXiv.org.
  published_on: '2026-07-02'
  doi: null
links:
  source: http://arxiv.org/abs/2607.02772v2
  open_access: https://arxiv.org/abs/2607.02772v2
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-07-14T19:52:23.610210Z'
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

