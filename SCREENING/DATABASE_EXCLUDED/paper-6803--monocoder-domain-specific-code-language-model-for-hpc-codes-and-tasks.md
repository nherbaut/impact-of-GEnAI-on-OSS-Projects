---
schema: paper-monitor/paper/v1
paper_id: 6803
record_type: PAPER
bibliography:
  title: 'MonoCoder: Domain-Specific Code Language Model for HPC Codes and Tasks'
  authors: Tal Kadosh, Niranjan Hasabnis, Vy A. Vo, Nadav Schneider, Neva Krien, Mihai Capotă, Abdul Wasay, Guy Tamir, Ted
    Willke, Nesreen K. Ahmed, Yuval Pinter, Timothy G. Mattson, Gal Oren
  abstract: With easier access to powerful compute resources, there is a growing trend in AI for software development to develop
    large language models (LLMs) to address a variety of programming tasks. Even LLMs applied to tasks from the high-performance
    computing (HPC) domain are huge in size and demand expensive compute resources for training. This is partly because LLMs
    for HPC tasks are obtained by finetuning existing LLMs that support several natural and/or programming languages. We found
    this design choice confusing - why do we need LLMs trained on natural languages and programming languages unrelated to
    HPC for HPC-specific tasks? In this line of work, we aim to question choices made by existing LLMs by developing smaller
    language models (LMs) for specific domains - we call them domain-specific LMs. Specifically, we start with HPC as a domain
    and build an HPC-specific LM, named MonoCoder,which is orders of magnitude smaller than existing LMs but delivers better
    performance on non-HPC and HPC codes. Specifically, we pretrained MonoCoderon an HPC-specific dataset (named HPCORPUS)
    of C and C++ programs mined from GitHub. We evaluated the performance of MonoCoder against state-of-the-art multi-lingual
    LLMs. Results demonstrate that MonoCoder,although much smaller than existing LMs, outperforms other LLMs on normalized-perplexity
    tests (in relation to model size) while also delivering competing CodeBLEU scores for high-performance and parallel code
    generations. In other words, results suggest that MonoCoderunderstands HPC code better than state-of-the-art LLMs. Mono
    Codersource code is available at our GitHub repository.
  publisher: 2024 IEEE High Performance Extreme Computing Conference Hpec 2024
  published_on: '2024-09-23'
  doi: 10.1109/hpec62836.2024.10938441
links:
  source: https://doi.org/10.1109/hpec62836.2024.10938441
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

