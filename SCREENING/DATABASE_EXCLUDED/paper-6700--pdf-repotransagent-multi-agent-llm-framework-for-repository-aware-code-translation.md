---
schema: paper-monitor/paper/v1
paper_id: 6700
record_type: PAPER
bibliography:
  title: '[PDF] RepoTransAgent: Multi-Agent LLM Framework for Repository-Aware Code Translation'
  authors: Ziqi Guan, Xin Yin, Zhiyuan Peng, Chao Ni
  abstract: 'Repository-aware code translation is critical for modernizing legacy systems, enhancing maintainability, and
    enabling interoperability across diverse programming languages. While recent advances in large language models (LLMs)
    have improved code translation quality, existing approaches face significant challenges in practical scenarios: insufficient
    contextual understanding, inflexible prompt designs, and inadequate error correction mechanisms. These limitations severely
    hinder accurate and efficient translation of complex, real-world code repositories. To address these challenges, we propose
    RepoTransAgent, a novel multi-agent LLM framework for repository-aware code translation. RepoTransAgent systematically
    decomposes the translation process into specialized subtasks-context retrieval, dynamic prompt construction, and iterative
    code refinement-each handled by dedicated agents. Our approach leverages retrieval-augmented generation (RAG) for contextual
    information gathering, employs adaptive prompts tailored to varying repository scenarios, and introduces a reflection-based
    mechanism for systematic error correction. We evaluate RepoTransAgent on hundreds of Java-C# translation pairs from six
    popular open-source projects. Experimental results demonstrate that RepoTransAgent significantly outperforms state-of-the-art
    baselines in both compile and pass rates. Specifically, RepoTransAgent achieves up to 55.34% compile rate and 45.84% pass
    rate. Comprehensive analysis confirms the robustness and generalizability of RepoTransAgent across different LLMs, establishing
    its effectiveness for real-world repository-aware code translation.'
  publisher: arXiv.org.
  published_on: '2025-08-25'
  doi: null
links:
  source: http://arxiv.org/abs/2508.17720v1
  open_access: https://arxiv.org/abs/2508.17720v1
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

