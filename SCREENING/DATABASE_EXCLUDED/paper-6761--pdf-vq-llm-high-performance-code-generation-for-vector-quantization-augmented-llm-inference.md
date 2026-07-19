---
schema: paper-monitor/paper/v1
paper_id: 6761
record_type: PAPER
bibliography:
  title: '[PDF] VQ-LLM: High-performance Code Generation for Vector Quantization Augmented LLM Inference'
  authors: Zihan Liu, X. Luo, Junxian Guo, Wentao Ni, Yangjie Zhou, Yue Guan, Christine C. Guo, Weihao Cui, Yu Feng, Minyi
    Guo, Yuhao Zhu, Minjia Zhang, Chen Jin, Jingwen Leng
  abstract: Vector quantization (VQ), which treats a vector as a compression unit, gains increasing research interests for
    its potential to accelerate large language models (LLMs). Compared to conventional element-wise quantization methods,
    VQ algorithms can compress weight and KV cache tensors in LLMs with a greater ratio while maintaining the high model accuracy.
    However, translating a VQ algorithm’s memory reduction into the actual latency improvement is challenging. We profile
    and analyze the current approach of integrating VQ into computation kernels and show that its major inefficiency lies
    in the poor access efficiency of codebooks in VQ algorithms and uncoordinated computation dataflow. Meanwhile, the diversity
    of VQ algorithms (e.g., different vector sizes and entry counts) and LLMs, computation kernels (e.g matrix-matrix/vector
    multiplication and attention computation) makes it impractical to manually craft efficient kernel implementations for
    each specific case. In this work, we design and implement VQ-LLM, an efficient fused VQ kernel generation framework. We
    first introduce a software abstraction called codebook cache to optimize codebook access efficiency and support the integration
    of VQ with various computations. The codebook cache adaptively stores different entries across the GPU’s memory hierarchy,
    including off-chip global memory, on-chip shared memory, and registers. Centered around the codebook cache, we design
    an efficient computation engine that optimizes memory traffic during computations involving codebooks. This compute engine
    adopts the codebook-centric dataflow and fusion optimizations. Additionally, we provide adaptive heuristics to tailor
    parameter selection in our optimizations to diverse VQ configurations. Our optimizations achieve the latency reduction
    of $\mathbf{6 4. 3 6 \%}$ to $\mathbf{9 9. 1 \%}$ compared to existing open-source implementations. A final comparison
    with state-of-the-art element-wise quantization methods like AWQ and QoQ shows that our VQ-LLM is practically viable,
    achieving latencies close or even better latencies to those at equivalent bit-widths, potentially offering greater accuracy.
  publisher: Proceedings International Symposium on High Performance Computer Architecture.
  published_on: '2025-03-01'
  doi: 10.1109/hpca61900.2025.00112
links:
  source: https://doi.org/10.1109/hpca61900.2025.00112
  open_access: https://arxiv.org/pdf/2503.02236
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

