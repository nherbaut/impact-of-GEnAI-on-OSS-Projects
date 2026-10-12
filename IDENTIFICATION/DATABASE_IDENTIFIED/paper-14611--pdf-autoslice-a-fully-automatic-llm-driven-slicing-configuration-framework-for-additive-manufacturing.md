---
schema: paper-monitor/paper/v1
paper_id: 14611
record_type: PAPER
bibliography:
  title: '[PDF] AutoSlice: A Fully Automatic LLM-driven Slicing Configuration Framework for Additive Manufacturing'
  authors: Syed Ziaul Bin Bashar, Jesus Diaz, Chaitanya Mahajan, Satyajayant Misra
  abstract: 'Producing reliable, production-quality 3D prints depends on an expert tuning multiple slicer parameters, which
    is a manual and graphical interface-bound process. While Large Language Models (LLMs) excel at reasoning tasks, their
    application to automate the slicing workflow remains underexplored. To address this challenge, we developed AutoSlice,
    a novel, modular framework that automates the generation of slicer configurations, which has an LLM as the core reasoning
    engine. The framework is designed to be scalable with a plug-and-play architecture, taking advantage of future versions
    in LLMs. The AutoSlice pipeline locally extracts non-invertible geometric features from a 3D model. These non-invertible
    design features, combined with schema-anchored rules and printer-material metadata, are then passed to an LLM agent, which
    reasons about the geometry and machine-specific heuristics to generate a complete and syntactically valid configuration
    file. This framework executes a headless command-line slicer, yielding machine-ready G-code. AutoSlice encapsulates expert
    knowledge, demonstrating a viable path to democratizing AM by enabling non-experts to reliably translate digital designs
    into high-quality objects. We conducted a comprehensive evaluation to demonstrate the framework’s robustness and modularity.
    We evaluated several versions of LLMs: both proprietary (Gemini-2.5-Flash, GPT-5-Mini) and open-source (Llama-3.2-3B-Instruct,
    Qwen-2.5-7B-Instruct), and evaluated also the Zero-Shot and One-Shot prompting strategies across two printers (Ender 3
    S1, Prusa XL) and materials (PLA, ABS). The results show that while smaller models struggle with reliability, larger LLMs
    achieve high efficacy. The One-Shot strategy with proprietary LLMs yielded over 97% valid G-code generation and printability,
    validated by successful physical prints.'
  publisher: Manufacturing Letters.
  published_on: '2026-10-01'
  doi: 10.1016/j.mfglet.2026.07.084
links:
  source: https://doi.org/10.1016/j.mfglet.2026.07.084
  open_access: https://www.sciencedirect.com/science/article/pii/S2213846326001355/pdf
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-12T04:09:22.005164Z'
workflow:
  state:
    id: IDENTIFICATION/DATABASE_IDENTIFIED
    label: Database identified
    prisma_bucket: DATABASE_IDENTIFIED
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

