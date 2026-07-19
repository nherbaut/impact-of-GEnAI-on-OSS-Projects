---
schema: paper-monitor/paper/v1
paper_id: 6811
record_type: PAPER
bibliography:
  title: '[PDF] Automatic Dataset Construction (ADC): Sample Collection, Data Curation, and Beyond'
  authors: Minghao Liu, Zonglin Di, Jiaheng Wei, Zhongruo Wang, Hengxiang Zhang, Ruixuan Xiao, Haoyu Wang, Jinlong Pang, Hao
    Chen, Ankit Shah, Hongxin Wei, Xinlei He, Zhaowei Zhao, Haobo Wang, Lei Feng, Jindong Wang, James Davis, Yang Liu
  abstract: 'Large-scale data collection is essential for developing personalized training data, mitigating the shortage of
    training data, and fine-tuning specialized models. However, creating high-quality datasets quickly and accurately remains
    a challenge due to annotation errors, the substantial time and costs associated with human labor. To address these issues,
    we propose Automatic Dataset Construction (ADC), an innovative methodology that automates dataset creation with negligible
    cost and high efficiency. Taking the image classification task as a starting point, ADC leverages LLMs for the detailed
    class design and code generation to collect relevant samples via search engines, significantly reducing the need for manual
    annotation and speeding up the data generation process. To demonstrate ADC at scale, we construct Clothing-ADC: a dataset
    of over 1 million images spanning 12 main classes and 12,000 fine-grained subclasses. Our automated curation achieves
    79\% agreement with human annotators and reduces label noise from 22.2\% to 10.7\%. Despite these advantages, ADC also
    encounters real-world challenges such as label errors (label noise) and imbalanced data distributions (label bias). We
    provide open-source software that incorporates existing methods for label error detection, robust learning under noisy
    and biased data, ensuring a higher-quality training data and more robust model training procedure. Furthermore, we design
    three benchmark datasets focused on label noise detection, label noise learning, and class-imbalanced learning. These
    datasets are vital because there are few existing datasets specifically for label noise detection, despite its importance.
    Finally, we evaluate the performance of existing popular methods on these datasets, thereby facilitating further research
    in the field.'
  publisher: arXiv.org.
  published_on: '2024-08-21'
  doi: null
links:
  source: http://arxiv.org/abs/2408.11338v2
  open_access: https://arxiv.org/abs/2408.11338v2
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

