---
schema: paper-monitor/paper/v1
paper_id: 6715
record_type: PAPER
bibliography:
  title: 'RTL++: Graph-enhanced LLM for RTL Code Generation'
  authors: Mohammad Akyash, Kimia Azar, Hadi Kamali
  abstract: As hardware design complexity escalates, there is an urgent need for advanced automation in electronic design
    automation (EDA). Traditional register transfer level (RTL) design methods are manual, time-consuming, and prone to errors.
    While commercial (instruction-tuned) large language models (LLMs) shows promising performance for automation, they pose
    security and privacy concerns. Open-source models offer alternatives; however, they frequently fall short in quality/correctness,
    largely due to limited, high-quality RTL code data essential for effective training and generalization. This paper proposes
    RTL++, a first-of-its-kind LLM-assisted method for RTL code generation that utilizes graph representations of code structures
    to enhance the quality of generated code. By encoding RTL code into a textualized control flowgraphs (CFG) and data flow
    graphs (DFG), RTL++ captures the inherent hierarchy, dependencies, and relationships within the code. This structured
    graph-based approach enhances the context available to LLMs, enabling them to better understand and generate instructions.
    By focusing on data generation through graph representations, RTL++ addresses the limitations of previous approaches that
    rely solely on code and suffer from lack of diversity. Experimental results demonstrate that RTL++ outperforms state-of-the-art
    models fine-tuned for RTL generation, as evaluated using the VerilogEval benchmark’s P ass@1/5/10 metric, as well as the
    RTLLM1.1 model, which highlight the effectiveness of graph-enhanced context in advancing the capabilities of LLM-assisted
    RTL code generation1.
  publisher: Proceedings 2025 IEEE International Conference on Llm Aided Design Iclad 2025
  published_on: '2025-06-26'
  doi: 10.1109/iclad65226.2025.00020
links:
  source: https://doi.org/10.1109/iclad65226.2025.00020
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

