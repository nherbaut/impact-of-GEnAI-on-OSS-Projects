---
schema: paper-monitor/paper/v1
paper_id: 6688
record_type: PAPER
bibliography:
  title: An Empirical Study of Exploring the Capabilities of Large Language Models in Code Learning
  authors: Shangqing Liu, Daya Guo, Jian Zhang, Wei Ma, Yanzhou Li, Yang Liu
  abstract: 'Since the advent of ChatGPT, large language models (LLMs) have attracted widespread attention from academia and
    industry. They have also brought significant changes to software engineering. However, until now, there has been a lack
    of comprehensive studies comparing LLMs with previous smaller code pre-trained models. To address this gap, we conduct
    a study in this paper to illustrate the performance of LLMs in different software engineering tasks. Specifically, we
    select three open-source large language models, CodeGen, LLaMA, and StarCoder, for the research targets, and our study
    is conducted from four aspects, including code syntax understanding, code semantic reasoning, encoding representation
    quality, and adaptation performance for different software engineering tasks to compare LLMs with previous code pre-trained
    models. Four aspects build on each other, forming important components of AI for Software Engineering. We conclude that:
    (1) Compared with previous smaller pre-trained models like CodeBERT, LLMs exhibit distinct trends in how they learn code
    syntax or semantics as the number of layers increases. Additionally, mastering code semantics proves to be more challenging,
    with semantic information usually learned in the final layers; (2) Causal decoder architecture with left-to-right attention
    masking does not perform well in zero-shot tasks; (3) For classification tasks, the mean vector representation generated
    by LLMs over a sequence tends to outperform the last token representation in the sequence; (4) Incorporating parameter-efficient
    fine-tuning techniques into LLMs for downstream tasks can help LLMs achieve better performance than previous code pre-trained
    models on code generation tasks but may not be optimal in some code understanding tasks; (5) LoRA emerges as a more effective
    PEFT technique for LLMs in downstream code-related tasks. We hope these findings will better guide future researchers
    in designing more powerful code models.'
  publisher: IEEE Transactions on Software Engineering
  published_on: '2025-09-16'
  doi: 10.1109/tse.2025.3609876
links:
  source: https://doi.org/10.1109/tse.2025.3609876
  open_access: null
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

