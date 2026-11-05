---
schema: paper-monitor/paper/v1
paper_id: 6607
record_type: PAPER
bibliography:
  title: '[PDF] Evaluating LLMs for Source Code Generation and Summarization Using Machine Learning Classification and Ranking'
  authors: Hussain Mahfoodh, Mustafa Hammad, Bassam A. Y. Alqaralleh, Aymen I. Zreikat
  abstract: The recent use of large language models (LLMs) in code generation and code summarization tasks has been widely
    adopted by the software engineering community. New LLMs are emerging regularly with improved functionalities, efficiency,
    and expanding data that allow models to learn more effectively. The lack of guidelines for selecting the right LLMs for
    coding tasks makes the selection a subjective choice by developers rather than a choice built on code complexity, code
    correctness, and linguistic similarity analysis. This research investigates the use of machine learning classification
    and ranking methods to select the best-suited open-source LLMs for code generation and code summarization tasks. This
    work conducts a comparison experiment on four open-source LLMs (Mistral, CodeLlama, Gemma 2, and Phi-3) and uses the MBPP
    coding question dataset to analyze code-generated outputs in terms of code complexity, maintainability, cyclomatic complexity,
    code structure, and LLM perplexity by collecting these as a set of features. An SVM classification problem is conducted
    on the highest correlated feature pairs, where the models are evaluated through performance metrics, including accuracy,
    area under the ROC curve (AUC), precision, recall, and F1 scores. The RankNet ranking methodology is used to evaluate
    code summarization model capabilities by measuring ROUGE and BERTScore accuracies between LLM code-generated summaries
    and the coding questions used from the dataset. The study results show a maximum accuracy of 49% for the code generation
    experiment, with the highest AUC score reaching 86% among the top four correlated feature pairs. The highest precision
    score reached is 90%, and the recall score reached up to 92%. Code summarization experiment results show Gemma 2 scored
    a 1.93 RankNet win probability score, and represented the highest ranking reached among other models. The phi3 model was
    the second-highest ranking with a 1.66 score. The research highlights the potential of machine learning to select LLMs
    based on coding metrics and paves the way for advancements in terms of accuracy, dataset diversity, and exploring other
    machine learning algorithms for other researchers.
  publisher: Computers.
  published_on: '2026-02-10'
  doi: 10.3390/computers15020119
links:
  source: https://doi.org/10.3390/computers15020119
  open_access: https://www.mdpi.com/2073-431X/15/2/119/pdf
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

