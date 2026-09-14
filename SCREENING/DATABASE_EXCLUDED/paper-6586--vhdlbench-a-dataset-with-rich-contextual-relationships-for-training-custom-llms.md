---
schema: paper-monitor/paper/v1
paper_id: 6586
record_type: PAPER
bibliography:
  title: VHDLBench — a Dataset with Rich Contextual Relationships for Training Custom LLMs
  authors: Arpit R. Sakhreliya, Manoj Franklin
  abstract: 'Due to the growing complexity of Integrated Circuits (ICs), automating HDL (Hardware Description Language) code
    generation is becoming important. Although large language models (LLMs) have become very proficient in generating computer
    programs, they have not been very successful in producing efficient VHDL code. A major reason for this is the lack of
    a suitable VHDL training set to train the LLM models. In this paper, we present a VHDL dataset built from 356 GitHub repositories
    comprising 39,000 VHDL files. We systematically preprocess each file to extract key structural components-libraries, packages,
    entities, architectures, components, process blocks, and interfile dependencies based on Unit Under Test (UUT), entities
    and component instantiations inter-file dependencies-using VHDLspecific heuristics and regular expressions, delivering
    rich contextual insights essential for fine-tuning and evaluating LLMs in VHDL code generation. Furthermore, to enable
    structured evaluation with VHDLBench, we introduce a module masking procedure that selectively removes a key module-entity,
    architecture, component, or a specific code segment-creating paired samples: a masked code segment and its corresponding
    removed snippet. This approach allows users to assess two key capabilities in LLMs: Code Structure Learning (CSL), which
    tests the model’s ability to generate coherent in-file structures, and Masked Module Completion (MMC), which evaluates
    how well the model infers missing modules and captures inter-file dependencies. By introducing VHDLBench, a structured
    and dependencyaware VHDL dataset, along with using rigorous evaluation metrics, this work establishes a foundation for
    advancing automated VHDL code generation. We evaluate deployable 7B-parameter code-oriented LLMs on the Masked Module
    Completion (MMC) task and fine-tune 7B models on VHDLBench, comparing their performance against the base models to quantify
    the benefits of domain-specific adaptation. Experimental results demonstrate that fine-tuning substantially improves structural
    accuracy, semantic alignment, and exact-match correctness in VHDL generation. We believe this work will contribute significantly
    to advancing the efficiency and accuracy of VHDL code generation, paving the way for more streamlined and scalable development
    of Integrated Circuits.'
  publisher: Proceedings International Symposium on Quality Electronic Design Isqed
  published_on: '2026-04-08'
  doi: 10.1109/isqed69900.2026.11534696
links:
  source: https://doi.org/10.1109/isqed69900.2026.11534696
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

