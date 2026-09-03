---
schema: paper-monitor/paper/v1
paper_id: 7910
record_type: PAPER
bibliography:
  title: '[PDF] EMRB: A Multi-Level Benchmark for Evaluating LLM Reasoning over Raw Electromagnetic Signals'
  authors: Mingxu Zhang, Ying Sun, Yuhan Li, Yang Ji, Dazhong Shen, Ke Zhang, Shan Huang
  abstract: Large language models (LLMs) are increasingly used as code agents for scientific and engineering analysis, but
    their ability to analyze raw physical-layer measurements remains untested. We introduce \textbf{EMRB} (\textbf{E}lectro\textbf{m}agnetic
    \textbf{R}easoning \textbf{B}enchmark), which evaluates whether LLMs can analyze raw I/Q data by writing and running code.
    EMRB contains 200 problems across five difficulty levels and 27 question types, from signal detection to OFDM design,
    generated from 11 signal types with verified ground truth. Unlike benchmarks built on preprocessed features or structured
    tables, EMRB provides only the raw capture; the quantities each question refers to must first be discovered through code.
    We evaluate 14 LLMs spanning proprietary, open-weight, and reasoning-oriented families. Scores range from 24.1\% to 78.9\%,
    with the mean dropping from 84.9\% on basic measurement to 21.2\% on system design. We also propose \textbf{ReconPilot},
    a structured method that separates signal reconnaissance, targeted analysis, and self-verification. Across three backbones,
    ReconPilot raises the overall score by 3.8 to 17.6 points and improves 13 of 15 backbone-level combinations tested. All
    data and code are publicly released in \href{https://github.com/mingxuZhang2/EMRB}{\textcolor{blue}{our GitHub repository}}.
  publisher: arXiv.org.
  published_on: '2026-08-25'
  doi: null
links:
  source: http://arxiv.org/abs/2608.24086v1
  open_access: https://arxiv.org/abs/2608.24086v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-08-26T07:54:09.025222Z'
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

