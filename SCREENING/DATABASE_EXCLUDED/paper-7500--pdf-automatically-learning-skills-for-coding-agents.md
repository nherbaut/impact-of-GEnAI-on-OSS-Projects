---
schema: paper-monitor/paper/v1
paper_id: 7500
record_type: PAPER
bibliography:
  title: '[PDF] Automatically Learning Skills for Coding Agents'
  authors: Shangyin Tan, Lakshya A Agrawal, Rohit Sandadi, Dan Klein, Koushik Sen, Alexandres G. Dimakis, Matei Zaharia
  abstract: 'Coding agents powered by large language models can solve a wide range of software engineering tasks, yet they
    often struggle on unfamiliar repositories whose conventions, testing patterns, and project structure differ from their
    training data. We introduce gskill, a fully automated pipeline that learns repository-specific skills, concise natural-language
    documents that capture the knowledge an agent needs to work effectively within a given codebase. gskill combines two components:
    (1) SWE-smith, a data-generation pipeline that creates diverse, verifiable software engineering tasks from any GitHub
    repository, and (2) optimize_anything, an evolutionary optimization loop that iteratively refines skill documents using
    LLM-generated feedback. Skills learned by gskill on a lightweight agent (Mini-SWE-Agent with GPT-5-mini) transfer directly
    to stronger agents: on the bleve repository, Claude Code with Claude Haiku 4.5 improves from 79.3% to 100.0% pass rate
    while also reducing average task duration from 173s to 130s. On jinja, Claude Haiku 4.5 improves from 93.9% to 98.5% while
    Claude Sonnet 4.5 maintains a perfect 100%. Our results demonstrate that automatically learned, repository-specific skills
    provide a lightweight and transferable mechanism for improving coding agent performance without model fine-tuning. gskill
    is publicly available at https://github.com/gepa-ai/gepa/tree/main/src/gepa/gskill.'
  publisher: Proceedings of the ACM Conference on AI and Agentic Systems Cais 2026.
  published_on: '2026-05-22'
  doi: 10.1145/3786335.3813196
links:
  source: https://doi.org/10.1145/3786335.3813196
  open_access: https://doi.org/10.1145/3786335.3813196
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-08-10T08:56:59.080052Z'
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

