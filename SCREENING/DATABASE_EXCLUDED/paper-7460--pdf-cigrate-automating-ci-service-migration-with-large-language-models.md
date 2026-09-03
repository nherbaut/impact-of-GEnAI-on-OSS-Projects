---
schema: paper-monitor/paper/v1
paper_id: 7460
record_type: PAPER
bibliography:
  title: '[PDF] CIgrate: Automating CI Service Migration with Large Language Models'
  authors: Md Nazmul Hossain, Taher A. Ghaleb
  abstract: 'Continuous Integration (CI) configurations often need to be migrated between services (e.g., Travis CI to GitHub
    Actions) as projects evolve due to changes in service capabilities, usage limits, or service deprecation. Previous studies
    reported that migration across CI services is a recurring need in open-source development. However, manual migration is
    time-consuming and error-prone. The state-of-the-art approach, CIMig, addresses this challenge by analyzing past migration
    examples to create service-specific rules and produce equivalent configurations across CI services. However, its relatively
    low accuracy (0.49 Cosine Similarity for Travis->GHA) raises concerns about the feasibility of rule-based CI migration
    alone. Meanwhile, Large Language Models (LLMs) have demonstrated strong capabilities in code generation and transformation
    tasks, suggesting potential to improve the automation, usability, and generalizability of CI configuration migration.
    This paper presents an empirical study assessing whether CI migration can be improved using LLMs. We propose CIgrate,
    an LLM-based framework for automatically migrating CI configurations, and compare it with CIMig using (a) zero-shot/few-shot
    prompting and (b) fine-tuning on a dataset of established CI migrations. We also evaluate practical deployment by submitting
    pull requests to active open-source projects. Our results show that CIgrate substantially outperforms CIMig: the fine-tuned
    Gemma 3 12B achieves 0.90 Cosine Similarity and 0.74 CrystalBLEU for Travis CI (Travis)->GitHub Actions (GHA) migrations
    (+82.2% and +295.5% over CIMig), while producing syntactically valid, immediately parseable YAML in 100% of cases, compared
    to 5.6% for CIMig. Even zero-shot LLMs outperform the rule-based baseline, demonstrating that LLM-based approaches provide
    a more practical and accurate solution for CI configuration migration.'
  publisher: arXiv.org.
  published_on: '2025-07-27'
  doi: null
links:
  source: http://arxiv.org/abs/2507.20402v2
  open_access: https://arxiv.org/abs/2507.20402v2
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-08-04T10:53:30.005608Z'
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

