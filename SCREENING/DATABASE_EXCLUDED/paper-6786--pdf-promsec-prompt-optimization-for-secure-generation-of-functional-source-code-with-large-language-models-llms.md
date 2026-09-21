---
schema: paper-monitor/paper/v1
paper_id: 6786
record_type: PAPER
bibliography:
  title: '[PDF] PromSec: Prompt Optimization for Secure Generation of Functional Source Code with Large Language Models (LLMs)'
  authors: Mahmoud Nazzal, Issa Khalil, Abdallah Khreishah, NhatHai Phan
  abstract: The capability of generating high-quality source code using large language models (LLMs) reduces software development
    time and costs. However, they often introduce security vulnerabilities due to training on insecure open-source data. This
    highlights the need for ensuring secure and functional code generation. This paper introduces PromSec, an algorithm for
    prom optimization for secure and functioning code generation using LLMs. In PromSec, we combine 1) code vulnerability
    clearing using a generative adversarial graph neural network, dubbed as gGAN, to fix and reduce security vulnerabilities
    in generated codes and 2) code generation using an LLM into an interactive loop, such that the outcome of the gGAN drives
    the LLM with enhanced prompts to generate secure codes while preserving their functionality. Introducing a new contrastive
    learning approach in gGAN, we formulate code-clearing and generation as a dual-objective optimization problem, enabling
    PromSec to notably reduce the number of LLM inferences. PromSec offers a cost-effective and practical solution for generating
    secure, functional code. Extensive experiments conducted on Python and Java code datasets confirm that PromSec effectively
    enhances code security while upholding its intended functionality. Our experiments show that while a state-of-the-art
    approach fails to address all code vulnerabilities, PromSec effectively resolves them. Moreover, PromSec achieves more
    than an order-of-magnitude reduction in operation time, number of LLM queries, and security analysis costs. Furthermore,
    prompts optimized with PromSec for a certain LLM are transferable to other LLMs across programming languages and generalizable
    to unseen vulnerabilities in training. This study is a step in enhancing the trustworthiness of LLMs for secure and functional
    code generation, supporting their integration into real-world software development.
  publisher: Ccs 2024 Proceedings of the 2024 ACM Sigsac Conference on Computer and Communications Security.
  published_on: '2024-12-02'
  doi: 10.1145/3658644.3690298
links:
  source: https://doi.org/10.1145/3658644.3690298
  open_access: https://dl.acm.org/doi/pdf/10.1145/3658644.3690298
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

