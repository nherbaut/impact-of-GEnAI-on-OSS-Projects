---
schema: paper-monitor/paper/v1
paper_id: 7246
record_type: PAPER
bibliography:
  title: '[PDF] DeepSWE: Measuring Frontier Coding Agents on Original, Long-Horizon Engineering Tasks'
  authors: Wenqi Huang, Charley Lee, Leonard Tng, Serena Ge
  abstract: 'DeepSWE is a benchmark of 113 original, long-horizon software engineering tasks for evaluating coding agents.
    Most public agentic coding benchmarks follow SWE-bench in mining merged fixes from public GitHub repositories, which creates
    two problems: the fixes and their discussion were likely seen during pretraining, so a high score can reflect recall rather
    than problem-solving; and each task is graded by the tests that shipped with its merged fix, which were written to confirm
    one specific fix rather than grade an arbitrary solution, so they can fail a correct alternative or pass an incomplete
    one. DeepSWE avoids both. Its tasks are written from scratch across 91 active open-source repositories and five languages
    and are never contributed back upstream, so their reference solutions stay out of the public record that model training
    scrapes; and each task is graded by a hand-written verifier that checks the requested functionality and accepts any implementation
    that provides it. When an independent LLM judge re-reviews graded runs, it disagrees with DeepSWE''s verifier about an
    order of magnitude less often than with SWE-Bench Pro''s inherited tests (1.4% versus 32.4%). Despite being about half
    the length of SWE-Bench Pro''s prompts, DeepSWE''s prompts describe tasks whose reference solutions touch 5.5x more code,
    and the benchmark separates frontier agents across a wider score band than the leaderboards on which they otherwise cluster.
    We release the benchmark, its verifiers, and the full record of evaluation trajectories.'
  publisher: arXiv.org.
  published_on: '2026-07-08'
  doi: null
links:
  source: http://arxiv.org/abs/2607.07946v1
  open_access: https://arxiv.org/abs/2607.07946v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-07-10T13:45:22.415685Z'
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

