---
schema: paper-monitor/paper/v1
paper_id: 12898
record_type: PAPER
bibliography:
  title: '[PDF] Quantifying Memorization Advantage in Code LLMs'
  authors: Djiré Albérick Euraste, Abdoul Kader Kaboré, Jordan Samhi, Earl T. Barr, Jacques Klein, Tegawendé François Bissyandé
  abstract: 'The lack of transparency regarding the code datasets used during LLM training creates substantial challenges
    in detecting, evaluating, and mitigating data leakage. This paper applies a perturbation-based approach to quantify the
    “memorization advantage” of LLMs across various coding tasks by measuring the performance gap between a model’s handling
    of data it has likely encountered during training versus novel inputs. Our comprehensive analysis examines 8 open-source
    code LLMs across 19 benchmark datasets spanning four distinct categories: standard code generation, code understanding,
    security vulnerability detection, and bug identification. The results reveal significant variations in sensitivity patterns,
    with models like StarCoder exhibiting substantially higher sensitivity scores (up to 0.8) on certain benchmarks like APPS
    compared to models like QwenCoder, which maintained consistently lower values (< 0.4) across most benchmarks, suggesting
    fundamental differences in their generalization process and their learned knowledge. Different task categories also showed
    distinct patterns, with code summarization demonstrating low sensitivity (< 0.3) and test generation tasks exhibiting
    significantly higher values (0.4-0.7, p < 0.001).'
  publisher: Proceedings 2026 IEEE ACM 48th International Conference on Software Engineering ICSE 2026.
  published_on: '2026-04-12'
  doi: 10.1145/3744916.3764554
links:
  source: https://doi.org/10.1145/3744916.3764554
  open_access: https://doi.org/10.1145/3744916.3764554
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-04T12:14:22.898402Z'
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

