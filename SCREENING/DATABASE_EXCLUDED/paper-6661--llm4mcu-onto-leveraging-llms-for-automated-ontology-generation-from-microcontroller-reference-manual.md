---
schema: paper-monitor/paper/v1
paper_id: 6661
record_type: PAPER
bibliography:
  title: 'Llm4mcu-Onto: Leveraging Llms for Automated Ontology Generation From Microcontroller Reference Manual'
  authors: Asmita Asmita, Grisha Bandodkar, Sujan Ghimire, Shaurya Srivastav, Soheil Salehi, Houman Homayoun
  abstract: This research addresses the challenges faced by firmware developers, security researchers, and enthusiasts who
    work with low-level microcontroller (MCU) documentation, which often spans hundreds of complex pages. Current structured
    approaches, such as System View Description (SVD), are widely used but suffer from manual, labor-intensive creation processes
    and inconsistent vendor adherence to CMSIS-SVD standards. We propose an automated solution using Large Language Models
    (LLMs) integrated with Retrieval-Augmented Generation (RAG), capable of effectively parsing and extracting structured
    information, including text, tables, and images from MCU reference manuals/ datasheets. To mitigate hallucination issues
    inherent in LLMs, we fine-tuned models using a dataset derived from CMSIS-SVD files, which we will open-source for community
    benefit. We also experimented with few-shot models. Additionally, we developed a standardized structured ontology that
    is automatically populated with information extracted through LLM assistance from the reference manuals of the corresponding
    MCUs. Our approach was evaluated using OpenAI's GPT-4o under one-shot, few-shot, and fine-tuning scenarios, all incorporating
    RAG. We also experimented with the open-source LLM model CodeLlama. The results highlight substantial improvements in
    automatically extracting peripheral details and information from MCU reference manuals. Thus, it helps reduce manual effort
    and time. The key contribution of our work lies in the tailored adaptation of existing AI techniques to address the specific
    challenges of embedded systems documentation. We perform standardized ontology creation and multimodal parsing. We leverage
    RAG with MCU-specific finetuning and few-shot learning to generate structured information from hundreds of pages of MCU
    documentation. This opens the door to potential applications such as more accurate firmware code generation and reverse
    engineering for security analysis.
  publisher: Proceedings IEEE International Conference on Computer Design VLSI in Computers and Processors
  published_on: '2025-11-10'
  doi: 10.1109/iccd65941.2025.00089
links:
  source: https://doi.org/10.1109/iccd65941.2025.00089
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

