---
schema: paper-monitor/paper/v1
paper_id: 6766
record_type: PAPER
bibliography:
  title: '[PDF] Deep Assessment of Code Review Generation Approaches: Beyond Lexical Similarity'
  authors: Yanjie Jiang, Hui Liu, Tianyi Chen, Fu Fan, Chunhao Dong, Kui Liu, Lu Zhang
  abstract: Code review is a standard practice for ensuring the quality of software projects, and recent research has focused
    extensively on automated code review. While significant advancements have been made in generating code reviews, the automated
    assessment of these reviews remains less explored, with existing approaches and metrics often proving inaccurate. Current
    metrics, such as BLEU, primarily rely on lexical similarity between generated and reference reviews. However, such metrics
    tend to underestimate reviews that articulate the expected issues in ways different from the references. In this paper,
    we explore how semantic similarity between generated and reference reviews can enhance the automated assessment of code
    reviews. We first present a benchmark called \textit{GradedReviews}, which is constructed by collecting real-world code
    reviews from open-source projects, generating reviews using state-of-the-art approaches, and manually assessing their
    quality. We then evaluate existing metrics for code review assessment using this benchmark, revealing their limitations.
    To address these limitations, we propose two novel semantic-based approaches for assessing code reviews. The first approach
    involves converting both the generated review and its reference into digital vectors using a deep learning model and then
    measuring their semantic similarity through Cosine similarity. The second approach generates a prompt based on the generated
    review and its reference, submits this prompt to ChatGPT, and requests ChatGPT to rate the generated review according
    to explicitly defined criteria. Our evaluation on the \textit{GradedReviews} benchmark indicates that the proposed semantic-based
    approaches significantly outperform existing state-of-the-art metrics in assessing generated code review, improving the
    correlation coefficient between the resulting scores and human scores from 0.22 to 0.47.
  publisher: arXiv.org.
  published_on: '2025-01-09'
  doi: null
links:
  source: http://arxiv.org/abs/2501.05176v1
  open_access: https://arxiv.org/abs/2501.05176v1
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

