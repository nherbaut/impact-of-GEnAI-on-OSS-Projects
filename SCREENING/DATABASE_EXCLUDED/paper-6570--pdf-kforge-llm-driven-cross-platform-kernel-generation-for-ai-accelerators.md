---
schema: paper-monitor/paper/v1
paper_id: 6570
record_type: PAPER
bibliography:
  title: '[PDF] KForge: LLM-Driven Cross-Platform Kernel Generation for AI Accelerators'
  authors: Taras Sereda, Burak Bartan, Ankita Nayak, Tom St. John, Natalie Serrino, Zain Asgar
  abstract: 'Production inference increasingly targets a heterogeneous mix of accelerators. Agentic pipelines interleave reasoning,
    tool calls, and multi-agent coordination, each with distinct compute and memory profiles. For optimal efficiency, each
    stage should run on the accelerator best suited to it. This creates a systems challenge: each pipeline now requires high-performance
    kernels across a growing set of hardware backends and programming models. Writing these kernels by hand is time-consuming,
    demands deep low-level expertise, and does not scale as kernel complexity grows. Recently, Large Language Models (LLMs)
    have been leveraged for automatic kernel generation, but challenges in low-level code generation and cross-backend generalization
    persist. We present KForge, a cross-platform framework built around an iterative refinement loop driven by two collaborating
    LLM-based agents: a generation agent that produces and progressively refines kernels using compilation and correctness
    feedback, and a performance-analysis agent that interprets profiling data, from programmatic APIs to GUI-based tools,
    and emits recommendations that steer the next round of synthesis. The loop alternates between functional passes, which
    drive a candidate to correctness, and optimization passes, which close the performance gap to hand-tuned baselines. We
    evaluate KForge on two backends with very different baseline reference availability. On NVIDIA B200, KForge achieves a
    2.12$\%$ improvement in end-to-end throughput compared to TensorRT-LLM on the gpt-oss-20b inference speed benchmark. On
    Intel Arc B580, KForge generates Triton kernels achieving a 5.13$\times$ geometric mean speedup over the faster of PyTorch
    eager and torch.compile on 37 GEMM + tail-ops workloads from KernelBench Level 2, primarily via operator fusion and mixed-precision
    execution.'
  publisher: arXiv.org.
  published_on: '2026-06-01'
  doi: null
links:
  source: http://arxiv.org/abs/2606.02963v1
  open_access: https://arxiv.org/abs/2606.02963v1
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

