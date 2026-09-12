---
schema: paper-monitor/paper/v1
paper_id: 6705
record_type: PAPER
bibliography:
  title: '[PDF] BugScope: Learn to Find Bugs Like Human'
  authors: Jinyao Guo, Chengpeng Wang, Dominic Deluca, Jinjie Liu, Zhuo Zhang, Xiangyu Zhang
  abstract: 'Software auditing is an increasingly critical task in the era of rapid code generation. While LLM-based auditors
    have demonstrated strong potential, their effectiveness remains limited by misalignment with the highly complex, domain-specific
    nature of bug detection. In this work, we introduce BugScope, a framework that mirrors how human auditors learn specific
    bug patterns from representative examples and apply this knowledge during code auditing. BugScope structures auditing
    into three steps: seed identification, context retrieval, and bug detection, and aligns LLMs to each step by analyzing
    real bug reports and mutated examples, and distilling concise, reusable guidelines. On a curated dataset of 33 real-world
    bugs from 21 widely used open-source projects, BugScope achieves 86.05\% precision and 87.88\% recall, corresponding to
    an F1 score of 0.87. By comparison, leading industrial tools such as Claude Code (with Claude Opus 4.6) and Cursor BugBot
    achieve F1 scores of only 0.51 and 0.43, respectively. Beyond benchmarks, large-scale evaluation on real-world projects
    such as the Linux kernel uncovered 184 previously unknown bugs, of which 78 have already been fixed and 7 explicitly confirmed
    by developers. Our code is available at https://github.com/jinyaoguo/BugScope'
  publisher: arXiv.org.
  published_on: '2025-07-21'
  doi: null
links:
  source: http://arxiv.org/abs/2507.15671v2
  open_access: https://arxiv.org/abs/2507.15671v2
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

