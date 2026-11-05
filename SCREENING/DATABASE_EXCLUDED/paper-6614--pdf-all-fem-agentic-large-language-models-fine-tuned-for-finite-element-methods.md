---
schema: paper-monitor/paper/v1
paper_id: 6614
record_type: PAPER
bibliography:
  title: '[PDF] ALL-FEM: Agentic Large Language models Fine-tuned for Finite Element Methods'
  authors: Rushikesh Deotale, Adithya Srinivasan, Yuan Tian, Tianyi Zhang, Pavlos Vlachos, Hector Gomez
  abstract: Finite element (FE) analysis guides the design and verification of nearly all manufactured objects. It is at the
    core of computational engineering, enabling simulation of complex physical systems, from fluids and solids to multiphysics
    systems. However, implementing FE codes and analyzing simulation results demands expertise across numerical analysis,
    continuum mechanics, and programming. Conventional Large Language Models (LLMs) can generate FE code, but they hallucinate,
    lack awareness of variational structures, and cannot close the loop from problem statement to a verified solution. Here,
    we propose ALL-FEM, an autonomous simulation system that integrates agentic AI with domain-specific, fine-tuned LLMs for
    FEniCS code generation across solid, fluid, and multiphysics applications. We construct a corpus of 1000+ verified FEniCS
    scripts by combining 500+ curated expert codes with a retrieval-augmented, multi-LLM pipeline that generates and filters
    codes for diverse PDEs, geometries, and boundary conditions. We used the corpus to fine-tune LLMs with 3B to 120B parameters.
    Our agentic framework orchestrates specialized agents, powered by fine-tuned LLMs, to formulate problems as PDEs, generate
    and debug code and visualize the results. We evaluated the system on 39 benchmarks that include problems of linear/nonlinear
    elasticity, plasticity, Newtonian/non-Newtonian flow, thermofluids, fluid-structure interaction, phase separation, and
    transport on moving domains. Embedded in a multi-agent workflow with runtime feedback, the best fine-tuned model (GPT
    OSS 120B) achieves code-level success of 71.79%, outperforming a non-agentic deployment of GPT 5 Thinking. By showing
    that relatively small, fine-tuned LLMs, orchestrated through agentic frameworks, can automate FE workflows, ALL-FEM offers
    a blueprint for autonomous simulation systems in computational science and engineering.
  publisher: arXiv.org.
  published_on: '2026-01-08'
  doi: null
links:
  source: http://arxiv.org/abs/2603.21011v2
  open_access: https://arxiv.org/abs/2603.21011v2
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

