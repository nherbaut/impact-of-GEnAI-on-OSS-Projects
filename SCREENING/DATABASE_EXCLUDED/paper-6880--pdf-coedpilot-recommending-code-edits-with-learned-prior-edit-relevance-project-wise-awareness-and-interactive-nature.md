---
schema: paper-monitor/paper/v1
paper_id: 6880
record_type: PAPER
bibliography:
  title: '[PDF] CoEdPilot: Recommending Code Edits with Learned Prior Edit Relevance, Project-wise Awareness, and Interactive
    Nature'
  authors: Chenyan Liu, Yufan Cai, Yun Lin, Yuhuan Huang, Yunrui Pei, Bo Jiang, Ping Yang, Jin Song Dong, Hong Mei
  abstract: Recent years have seen the development of LLM-based code generation. Compared to generating code in a software
    project, incremental code edits are empirically observed to be more frequent. The emerging code editing approaches usually
    formulate the problem as generating an edit based on known relevant prior edits and context. However, practical code edits
    can be more complicated. First, an editing session can include multiple (ir)relevant edits to the code under edit. Second,
    the inference of the subsequent edits is non-trivial as the scope of its ripple effect can be the whole project. In this
    work, we propose CoEdPilot, an LLM-driven solution to recommend code edits by discriminating the relevant edits, exploring
    their interactive natures, and estimating its ripple effect in the project. Specifically, CoEdPilot orchestrates multiple
    neural transformers to identify what and how to edit in the project regarding both edit location and edit content. When
    a user accomplishes an edit with an optional editing description, a Subsequent Edit Analysis first reports the most relevant
    files in the project with what types of edits (e.g., keep, insert, and replace) can happen for each line of their code.
    Next, an Edit-content Generator generates concrete edit options for the lines of code, regarding its relevant prior changes
    reported by an Edit-dependency Analyzer. Lastly, both the Subsequent Edit Analysis and the Edit-content Generator capture
    relevant prior edits as feedback to readjust their recommendations. We train our models by collecting over 180K commits
    from 471 open-source projects in 5 programming languages. Our extensive experiments show that CoEdPilot can well predict
    the edits (i.e., predicting edit location with an accuracy of 70.8%-85.3%, and the edit content with an exact match rate
    of 41.8% and BLEU4 score of 60.7)...
  publisher: arXiv.org.
  published_on: '2024-08-03'
  doi: null
links:
  source: http://arxiv.org/abs/2408.01733v1
  open_access: https://arxiv.org/abs/2408.01733v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-07-01T02:30:16.053229Z'
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

