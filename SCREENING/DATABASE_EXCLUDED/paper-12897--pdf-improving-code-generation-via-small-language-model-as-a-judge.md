---
schema: paper-monitor/paper/v1
paper_id: 12897
record_type: PAPER
bibliography:
  title: '[PDF] Improving Code Generation via Small Language Model-as-a-judge'
  authors: Giuseppe Crupi, Rosalia Tufano, Gabriele Bavota
  abstract: Large language models (LLMs) have shown remarkable capabilities in automated code generation. While effective
    for mainstream languages, they may underperform on less common or domain-specific languages, prompting companies to develop
    in-house code generators. While open-source models can be trained for this, only LLMs with tens of billions of parameters
    match the performance of commercial tools, demanding costly training and deployment. Recent work proposed supporting code
    generation with smaller models (SLMs) by generating multiple candidate solutions and using another SLM to select the most
    likely correct one. The most recent work in this area is the one by Sun et al. [29] presenting RankEF, a T5 model trained
    to rank code solutions using both execution-based and non-execution-based information. However, Sun et al. do not assess
    the T5 ranker’s classification accuracy, that is, how often it misjudges correct implementations as incorrect or vice
    versa, leaving open questions about the reliability of LMs as code correctness judges for other tasks (e.g., automated
    code review). Moreover, their experiments involve relatively old models, making it unclear the extent to which such a
    methodology would still help companies in cheaply training their own code generators with performance comparable to those
    of massive LLMs. We present a study addressing these limitations. We train several state-of-the-art SLMs as code correctness
    judges and assess their ability to discriminate between correct and wrong implementations. We show that modern SLMs outperform
    RankEF, even without exploiting execution-based information. When used as code rankers, they achieve higher performance
    gains than RankEF and perform competitively with LLMs 5–25 × larger, at a fraction of the cost.
  publisher: Proceedings 2026 IEEE ACM 48th International Conference on Software Engineering ICSE 2026.
  published_on: '2026-04-12'
  doi: 10.1145/3744916.3787822
links:
  source: https://doi.org/10.1145/3744916.3787822
  open_access: https://doi.org/10.1145/3744916.3787822
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-04T12:14:22.898402Z'
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

