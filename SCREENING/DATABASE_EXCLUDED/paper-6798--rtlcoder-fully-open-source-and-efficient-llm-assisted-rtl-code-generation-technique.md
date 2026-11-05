---
schema: paper-monitor/paper/v1
paper_id: 6798
record_type: PAPER
bibliography:
  title: 'RTLCoder: Fully Open-Source and Efficient LLM-Assisted RTL Code Generation Technique'
  authors: Shang Liu, Wenji Fang, Yao Lu, Jing Wang, Qijun Zhang, Hongce Zhang, Zhiyao Xie
  abstract: The automatic generation of RTL code (e.g., Verilog) using natural language instructions and large language models
    (LLMs) has attracted significant research interest recently. However, most existing approaches heavily rely on commercial
    LLMs, such as ChatGPT, while open-source LLMs tailored for this specific design generation task exhibit notably inferior
    performance. The absence of high-quality open-source solutions restricts the flexibility and data privacy of this emerging
    technique. In this study, we present a new customized LLM solution with a modest parameter count of only 7B, achieving
    better performance than GPT-3.5 on all representative benchmarks for RTL code generation. Especially, it outperforms GPT-4
    in VerilogEval Machine benchmark. This remarkable balance between accuracy and efficiency is made possible by leveraging
    our new RTL code dataset and a customized LLM algorithm, both of which have been made fully open-source. Furthermore,
    we have successfully quantized our LLM to 4-bit with a total size of 4 GB, enabling it to function on a single laptop
    with only slight performance degradation. This efficiency allows the RTL generator to serve as a local assistant for engineers,
    ensuring all design privacy concerns are addressed.
  publisher: IEEE Transactions on Computer Aided Design of Integrated Circuits and Systems
  published_on: '2024-10-17'
  doi: 10.1109/tcad.2024.3483089
links:
  source: https://doi.org/10.1109/tcad.2024.3483089
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

