---
schema: paper-monitor/paper/v1
paper_id: 6571
record_type: PAPER
bibliography:
  title: '[PDF] DFlare: Scaling Up Draft Capacity for Block Diffusion Speculative Decoding'
  authors: Jiebin Zhang, Zhenghan Yu, Song Liu, Eugene J. Yu, Zheng Li, Dawei Zhu, Jiangshan Duo, Weimin Xiong, Yifan Song,
    Guanghua Yu, Jianchen Zhu, Sujian Li
  abstract: 'Block diffusion speculative decoding accelerates LLM inference by predicting all tokens within a block simultaneously
    for the target model to verify in parallel. Predicting an entire block at once requires a sufficiently capable draft model
    and effective utilization of the target model''s internal knowledge. However, the state-of-the-art method DFlash constrains
    all draft layers to share a single fused representation derived from only a few target layers, limiting per-layer expressiveness
    and hindering further scaling of draft capacity. In this paper, we present \modelname, which flares out the narrow conditioning
    bottleneck of DFlash through a lightweight layer-wise fusion mechanism: each draft layer attends to its own learnable
    combination of a broad set of target layers at negligible overhead, simultaneously injecting richer target knowledge and
    providing every draft layer with a distinct input. This enhanced per-layer expressiveness enables scaling the draft model
    to deeper architectures with consistent gains. We further scale training data from 800K to 2.4M samples to fully exploit
    the enlarged capacity. On six benchmarks spanning mathematical reasoning, code generation, and conversation, \modelname
    attains average wall-clock speedups of 5.52x on Qwen3-4B, 5.46x on Qwen3-8B, and 3.91x on GPT-OSS-20B, improving over
    DFlash by roughly 11\%, 8\%, and 5\% respectively. Our code is available at https://github.com/Tencent/AngelSlim.'
  publisher: arXiv.org.
  published_on: '2026-06-01'
  doi: null
links:
  source: http://arxiv.org/abs/2606.02091v2
  open_access: https://arxiv.org/abs/2606.02091v2
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

