---
schema: paper-monitor/paper/v1
paper_id: 6716
record_type: PAPER
bibliography:
  title: 'VeriContaminated: Assessing LLM-Driven Verilog Coding for Data Contamination'
  authors: Zeng Wang, Minghao Shao, Jitendra Bhandari, Likhitha Mankali, Ramesh Karri, Ozgur Sinanoglu, Muhammad Shafique,
    Johann Knechtel
  abstract: Large Language Models (LLMs) have revolutionized code generation, achieving exceptional results on various established
    benchmarking frameworks. However, concerns about data contamination—where benchmark data inadvertently leaks into pre-training
    or fine-tuning datasets—raise questions about the validity of these evaluations. While this issue is known, limiting the
    industrial adoption of LLM-driven software engineering, hardware coding has received little to no attention regarding
    these risks. For the first time, we analyze state-of-the-art (SOTA) evaluation frameworks for Verilog code generation
    (VerilogEval and RTLLM), using established methods for contamination detection (CCD and Min-K% Prob). We cover SOTA commercial
    and open-source LLMs (CodeGen2.5, Minitron 4b, Mistral 7b, phi-4 mini, LLaMA-{1,2,3.1}, GPT- {2,3.5,4o} , Deepseek-Coder,
    and CodeQwen 1.5), in baseline and fine-tuned models (RTLCoder and Verigen). Our study confirms that data contamination
    is a critical concern. We explore mitigations and the resulting trade-offs for code quality vs fairness (i.e., reducing
    contamination toward unbiased benchmarking). Codes are open-sourced at https://github.com/DfX-NYUAD/VeriContaminated.
  publisher: Proceedings 2025 IEEE International Conference on Llm Aided Design Iclad 2025
  published_on: '2025-06-26'
  doi: 10.1109/iclad65226.2025.00017
links:
  source: https://doi.org/10.1109/iclad65226.2025.00017
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

