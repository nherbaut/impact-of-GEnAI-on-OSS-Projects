---
schema: paper-monitor/paper/v1
paper_id: 6598
record_type: PAPER
bibliography:
  title: '[PDF] Theory of Code Space: Do Code Agents Understand Software Architecture?'
  authors: Grigory Sapunov
  abstract: 'AI code agents excel at isolated tasks yet struggle with multi-file software engineering requiring architectural
    understanding. We introduce Theory of Code Space (ToCS), a benchmark that evaluates whether agents can construct, maintain,
    and update coherent architectural beliefs during codebase exploration. Agents explore procedurally generated codebases
    under partial observability -- opening files under a budget -- and periodically externalize their belief state as structured
    JSON, producing a time-series of architectural understanding. Three findings emerge from experiments with four baselines
    and six frontier LLMs. First, the Active-Passive Gap is model-dependent: one model builds better maps through active exploration
    than from seeing all files at once, while another shows the opposite -- revealing that active exploration is itself a
    non-trivial capability absent from some models. Second, retaining structured belief maps in context acts as self-scaffolding
    for some models but not others, showing that the mechanism is model-dependent. Third, belief state maintenance varies
    dramatically: a smaller model maintains perfectly stable beliefs across probes while its larger sibling suffers catastrophic
    belief collapse -- forgetting previously-discovered components between probes. We release ToCS as open-source software.
    Code: https://github.com/che-shr-cat/tocs'
  publisher: arXiv.org.
  published_on: '2026-02-28'
  doi: null
links:
  source: http://arxiv.org/abs/2603.00601v4
  open_access: https://arxiv.org/abs/2603.00601v4
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

