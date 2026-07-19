---
schema: paper-monitor/paper/v1
paper_id: 6615
record_type: PAPER
bibliography:
  title: 'Steer Your Model: Secure Code Generation With Contrastive Decoding'
  authors: Li Huang, Meng Yan, Tao Yin, Weifeng Sun, Zhongxin Liu, Hongyu Zhang, David Lo
  abstract: Large Language Models (LLMs) specialized in code have demonstrated impressive capabilities in various programming
    tasks such as code generation. However, these models often generate vulnerable code due to inherent flaws in training
    datasets derived from large-scale, unfiltered open-source repositories. Existing methods like SVEN (prefix tuning) and
    CoSec (supervised co-decoding) attempt to address these risks but face challenges with transferability or inflexible security
    constraints. To mitigate these issues, we propose SCoDE, a two-stage approach for secure and functionally correct code
    generation. After an initial functional tuning phase, we integrate a plug-andplay security steering matrix at the model’s
    output embedding layer. This matrix can be transferred across models without modifying their original weights. During
    inference, we introduce a novel contrastive decoding mechanism that adaptively balances the base model’s functional logits
    with positive and negative security steering signals. Extensive experiments on 60 security scenarios and two standard
    benchmarks (HumanEval, MBPP) using StarCoder, Qwen2.5-Coder, and CodeLlama demonstrate that SCoDE enhances security while
    maintaining functional correctness. On average, SCoDE improves security by 28.09% over the original models, 12.07% over
    CoSec, and 4.82% over SVEN. For functional correctness, it achieves average gains of 55.03% on HumanEval and 41.81% on
    MBPP over the original models.
  publisher: IEEE Transactions on Software Engineering
  published_on: '2026-01-05'
  doi: 10.1109/tse.2025.3650127
links:
  source: https://doi.org/10.1109/tse.2025.3650127
  open_access: null
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

