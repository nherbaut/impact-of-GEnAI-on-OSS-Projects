---
schema: paper-monitor/paper/v1
paper_id: 6619
record_type: PAPER
bibliography:
  title: '[PDF] Automating Android Build Repair: Bridging the Reasoning-Execution Gap in LLM Agents with Domain-Specific Tools'
  authors: Ha Min Son, Huan Ren, Xin Liu, Zhe Zhao
  abstract: 'Android is the largest mobile platform, yet automatically building applications remains a practical challenge.While
    Large Language Models (LLMs) show promise for code repair, their use for fixing Android build errors remains underexplored.To
    address this gap, we first introduce AndroidBuildBench, a benchmark of 1,019 build failures curated from the commit histories
    of 43 open-source Android projects.Each problem is paired with a verified solution from a subsequent commit, ensuring
    that fixes are feasible.Second, we propose GradleFixer, an LLM agent with domain-specific tools for inspecting and manipulating
    the Gradle build environment.GradleFixer achieves a resolve rate of 81.4% (pass@1), significantly outperforming a state-of-the-art
    coding agent that relies on a general-purpose shell.GradleFixer''s success suggests that while LLMs possess the highlevel
    knowledge to solve these failures, they struggle to translate this knowledge into effective low-level actions using a
    general-purpose shell.We demonstrate the effectiveness of a strategy we term Tool Bridging, which replaces general-purpose
    shell commands with domainaware abstractions.We hypothesize this approach works through two mechanisms: 1) it provides
    tools in an API-like format that LLMs use more reliably, and 2) it constrains the action space to relevant operations.This
    approach bridges the gap between the model''s high-level reasoning and effective low-level execution.'
  publisher: Eacl 2026 19th Conference of the European Chapter of the Association for Computational Linguistics Proceedings
    of the Conference Vol 1 Long Papers.
  published_on: '2026-01-01'
  doi: 10.18653/v1/2026.eacl-long.195
links:
  source: https://doi.org/10.18653/v1/2026.eacl-long.195
  open_access: https://aclanthology.org/2026.eacl-long.195.pdf
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

