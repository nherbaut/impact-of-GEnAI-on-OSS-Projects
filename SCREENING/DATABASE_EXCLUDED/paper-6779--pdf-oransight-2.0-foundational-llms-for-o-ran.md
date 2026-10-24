---
schema: paper-monitor/paper/v1
paper_id: 6779
record_type: PAPER
bibliography:
  title: '[PDF] ORANSight-2.0: Foundational LLMs for O-RAN'
  authors: Pranshav Gajjar, Vijay K. Shah
  abstract: Despite the transformative impact of Large Language Models (LLMs) across critical domains such as healthcare,
    customer service, and business marketing, their integration into Open Radio Access Networks (O-RAN) remains limited. This
    gap is primarily due to the absence of domain-specific foundational models, with existing solutions often relying on general-purpose
    LLMs that fail to address the unique challenges and technical intricacies of O-RAN. To bridge this gap, we introduce ORANSight-2.0
    (O-RAN Insights), a pioneering initiative to develop specialized foundational LLMs tailored for O-RAN. Built on 18 models
    spanning five open-source LLM frameworks—Mistral, Qwen, Llama, Phi, and Gemma—ORANSight-2.0 fine-tunes models ranging
    from 1B to 70B parameters, significantly reducing reliance on proprietary, closed-source models while enhancing performance
    in O-RAN-specific tasks. At the core of ORANSight-2.0 is RANSTRUCT, a novel Retrieval-Augmented Generation (RAG)-based
    instruction-tuning framework that employs two LLM agents—a Mistral-based Question Generator and a Qwen-based Answer Generator—to
    create high-quality instruction-tuning datasets. The generated dataset is then used to fine-tune the 18 pre-trained open-source
    LLMs via QLoRA. To evaluate ORANSight-2.0, we introduce srsRANBench, a novel benchmark designed for code generation and
    codebase understanding in the context of srsRAN, a widely used 5G O-RAN stack. Additionally, we leverage ORAN-Bench-13K,
    an existing benchmark for assessing O-RAN-specific knowledge. Our comprehensive evaluations demonstrate that ORANSight-2.0
    models outperform general-purpose and closed-source models, such as ChatGPT-4o and Gemini, by 5.421% on ORANBench and
    18.465% on srsRANBench, achieving superior performance while maintaining lower computational and energy costs. We also
    experiment with RAG-augmented variants of ORANSight-2.0 models and observe that RAG augmentation improves performance
    by an average of 6.35% across benchmarks, achieving the best overall cumulative score of 0.854, which is 12.37% better
    than the leading closed-source alternative. We thoroughly evaluate the energy characteristics of ORANSight-2.0, demonstrating
    its efficiency in training, inference, and inference with RAG augmentation, ensuring optimal performance while maintaining
    low computational and energy costs. Additionally, the best ORANSight-2.0 configuration is compared against the available
    telecom LLMs, where our proposed model outperformed them with an average improvement of 27.96%.
  publisher: IEEE Transactions on Machine Learning in Communications and Networking.
  published_on: '2025-01-01'
  doi: 10.1109/tmlcn.2025.3592658
links:
  source: https://doi.org/10.1109/tmlcn.2025.3592658
  open_access: https://doi.org/10.1109/tmlcn.2025.3592658
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

