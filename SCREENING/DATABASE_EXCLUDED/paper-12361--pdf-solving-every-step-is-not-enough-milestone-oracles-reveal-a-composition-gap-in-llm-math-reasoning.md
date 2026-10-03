---
schema: paper-monitor/paper/v1
paper_id: 12361
record_type: PAPER
bibliography:
  title: '[PDF] Solving Every Step Is Not Enough: Milestone Oracles Reveal a Composition Gap in LLM Math Reasoning'
  authors: Zhuohan Wang, Haoran Ma, Tianyu Wu, Yuanlin Duan, Zichun Liao, Jieming Yu
  abstract: Large language models (LLMs) can solve every intermediate step of a multi-step math problem on its own and still
    fail the full problem, even when given a roadmap of the steps and all of their answers. We introduce OracleLadder, a diagnostic
    evaluation that locates where LLM math reasoning fails by giving the model increasing levels of oracle help. For each
    problem, a teacher model writes a fixed roadmap of intermediate sub-goals (milestones), and a deterministic symbolic verifier
    grades every answer. Testing the model with no help, with the roadmap, with the roadmap plus the milestone answers, and
    on each milestone alone sorts each failure into one of five reasoning gaps. On 354 NuminaMath problems and six models
    from 8B to 671B parameters (Qwen3, gpt-oss, Llama 3.3, DeepSeek-V3.1), the largest gap for every model is the composition
    gap, a stricter form of the compositionality gap. It covers 33-48% of problems, and 24-37% after removing problems that
    an LLM review flags as grading errors. Accuracy and milestone-help recovery rank the two strongest models differently,
    and two RLVR runs with similar accuracy gains move problems differently. The roadmap effect replicates on MATH500 and
    AIME 2024/25, per-problem recovery agrees for 83-87% of problems under an independent second teacher, and the help ladder
    carries over to code generation. We release the data, roadmaps, prompts, and code at https://github.com/slark-prime/OracleLadder.
  publisher: arXiv.org.
  published_on: '2026-09-26'
  doi: null
links:
  source: http://arxiv.org/abs/2609.32235v1
  open_access: https://arxiv.org/abs/2609.32235v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-09-29T06:05:48.754839Z'
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

