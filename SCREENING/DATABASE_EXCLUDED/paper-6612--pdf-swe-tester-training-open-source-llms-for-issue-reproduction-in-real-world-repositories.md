---
schema: paper-monitor/paper/v1
paper_id: 6612
record_type: PAPER
bibliography:
  title: '[PDF] SWE-Tester: Training Open-Source LLMs for Issue Reproduction in Real-World Repositories'
  authors: Aditya Bharat Soni, Rajat Ghosh, Vaishnavi Bhargava, Valerie Chen, Debojyoti Dutta
  abstract: Software testing is crucial for ensuring the correctness and reliability of software systems. Automated generation
    of issue reproduction tests from natural language issue descriptions enhances developer productivity by simplifying root
    cause analysis, promotes test-driven development -- "test first, write code later", and can be used for improving the
    effectiveness of automated issue resolution systems like coding agents. Existing methods proposed for this task predominantly
    rely on closed-source LLMs, with limited exploration of open models. To address this, we propose SWE-Tester -- a novel
    pipeline for training open-source LLMs to generate issue reproduction tests. First, we curate a high-quality training
    dataset of 41K instances from 2.6K open-source GitHub repositories and use it to train LLMs of varying sizes and families.
    The fine-tuned models achieve absolute improvements of up to 10\% in success rate and 21\% in change coverage on SWT-Bench
    Verified. Further analysis shows consistent improvements with increased inference-time compute, more data, and larger
    models. These results highlight the effectiveness of our framework for advancing open-source LLMs in this domain.
  publisher: arXiv.org.
  published_on: '2026-01-20'
  doi: null
links:
  source: http://arxiv.org/abs/2601.13713v1
  open_access: https://arxiv.org/abs/2601.13713v1
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

