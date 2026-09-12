---
schema: paper-monitor/paper/v1
paper_id: 6805
record_type: PAPER
bibliography:
  title: '[PDF] CoEdPilot: Recommending Code Edits with Learned Prior Edit Relevance, Project-wise Awareness, and Interactive
    Nature'
  authors: Chenyan Liu, Yufan Cai, Yun Lin, Yu-Huan Huang, Y.-H. Pei, Bo Jiang, Ping Yang, Jin Song Dong, Hong Mei
  abstract: Recent years have seen the development of LLM-based code generation. Compared to generating code in a software
    project, incremental code edits are empirically observed to be more frequent. The emerging code editing approaches usually
    formulate the problem as generating an edit based on known relevant prior edits and context. However, practical code edits
    can be more complicated. First, an editing session can include multiple (ir)relevant edits to the code under edit. Second,
    the inference of the subsequent edits is non-trivial as the scope of its ripple effect can be the whole project. In this
    work, we propose CoEdPilot, an LLM-driven solution to recommend code edits by discriminating the relevant edits, exploring
    their interactive natures, and estimating its ripple effect in the project. Specifically, CoEdPilot orchestrates multiple
    neural transformers to identify what and how to edit in the project regarding both edit location and edit content. When
    a user accomplishes an edit with an optional editing description, an Subsequent Edit Analysis first reports the most relevant
    files in the project with what types of edits (e.g., keep, insert, and replace) can happen for each line of their code.
    Next, an Edit-content Generator generates concrete edit options for the lines of code, regarding its relevant prior changes
    reported by an Edit-dependency Analyzer. Last, both the Subsequent Edit Analysis and the Edit-content Generator capture
    relevant prior edits as feedback to readjust their recommendations. We train our models by collecting over 180K commits
    from 471 open-source projects in 5 programming languages. Our extensive experiments show that (1) CoEdPilot can well predict
    the edits (i.e., predicting edit location with accuracy of 70.8%-85.3%, and the edit content with exact match rate of
    41.8% and BLEU4 score of 60.7); (2) CoEdPilot can well boost existing edit generators such as GRACE and CCT5 on exact
    match rate by 8.57% points and BLEU4 score by 18.08. Last, our user study on 18 participants with 3 editing tasks (1)
    shows that CoEdPilot can be effective in assisting users to edit code in comparison with Copilot, and (2) sheds light
    on the future improvement of the tool design. The video demonstration of our tool is available at https://sites.google.com/view/coedpilot/home.
  publisher: Issta 2024 Proceedings of the 33rd ACM SIGSOFT International Symposium on Software Testing and Analysis.
  published_on: '2024-09-11'
  doi: 10.1145/3650212.3652142
links:
  source: https://doi.org/10.1145/3650212.3652142
  open_access: https://arxiv.org/pdf/2408.01733
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-06-30T13:29:23.865282Z'
workflow:
  state:
    id: RETRIEVAL/DATABASE_SOUGHT_FOR_RETRIEVAL
    label: Database sought for retrieval
    prisma_bucket: DATABASE_SOUGHT_FOR_RETRIEVAL
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

