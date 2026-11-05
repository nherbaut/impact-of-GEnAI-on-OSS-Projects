---
schema: paper-monitor/paper/v1
paper_id: 6876
record_type: PAPER
bibliography:
  title: '[PDF] Data-efficient LLM Fine-tuning for Code Generation'
  authors: Weijie Lv, Xuan Xia, Sheng-Jun Huang
  abstract: Large language models (LLMs) have demonstrated significant potential in code generation tasks. However, there
    remains a performance gap between open-source and closed-source models. To address this gap, existing approaches typically
    generate large amounts of synthetic data for fine-tuning, which often leads to inefficient training. In this work, we
    propose a data selection strategy in order to improve the effectiveness and efficiency of training for code-based LLMs.
    By prioritizing data complexity and ensuring that the sampled subset aligns with the distribution of the original dataset,
    our sampling strategy effectively selects high-quality data. Additionally, we optimize the tokenization process through
    a "dynamic pack" technique, which minimizes padding tokens and reduces computational resource consumption. Experimental
    results show that when training on 40% of the OSS-Instruct dataset, the DeepSeek-Coder-Base-6.7B model achieves an average
    performance of 66.9%, surpassing the 66.1% performance with the full dataset. Moreover, training time is reduced from
    47 minutes to 34 minutes, and the peak GPU memory decreases from 61.47 GB to 42.72 GB during a single epoch. Similar improvements
    are observed with the CodeLlama-Python-7B model on the Evol-Instruct dataset. By optimizing both data selection and tokenization,
    our approach not only improves model performance but also improves training efficiency.
  publisher: arXiv.org.
  published_on: '2025-04-17'
  doi: null
links:
  source: http://arxiv.org/abs/2504.12687v1
  open_access: https://arxiv.org/abs/2504.12687v1
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

