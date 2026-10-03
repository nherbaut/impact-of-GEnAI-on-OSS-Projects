---
schema: paper-monitor/paper/v1
paper_id: 6695
record_type: PAPER
bibliography:
  title: '[PDF] Code Review Without Borders: Evaluating Synthetic vs. Real Data for Review Recommendation'
  authors: Yogev Cohen, Dudi Ohayon, Romy Somkin, Yehudit Aperstein, Alexander Apartsin
  abstract: 'Automating the decision of whether a code change requires manual review is vital for maintaining software quality
    in modern development workflows. However, the emergence of new programming languages and frameworks creates a critical
    bottleneck: while large volumes of unlabelled code are readily available, there is an insufficient amount of labelled
    data to train supervised models for review classification. We address this challenge by leveraging Large Language Models
    (LLMs) to translate code changes from well-resourced languages into equivalent changes in underrepresented or emerging
    languages, generating synthetic training data where labelled examples are scarce. We assume that although LLMs have learned
    the syntax and semantics of new languages from available unlabelled code, they have yet to fully grasp which code changes
    are considered significant or review-worthy within these emerging ecosystems. To overcome this, we use LLMs to generate
    synthetic change examples and train supervised classifiers on them. We systematically compare the performance of these
    classifiers against models trained on real labelled data. Our experiments across multiple GitHub repositories and language
    pairs demonstrate that LLM-generated synthetic data can effectively bootstrap review recommendation systems, narrowing
    the performance gap even in low-resource settings. This approach provides a scalable pathway to extend automated code
    review capabilities to rapidly evolving technology stacks, even in the absence of annotated data.'
  publisher: arXiv.org.
  published_on: '2025-09-05'
  doi: null
links:
  source: http://arxiv.org/abs/2509.04810v1
  open_access: https://arxiv.org/abs/2509.04810v1
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

