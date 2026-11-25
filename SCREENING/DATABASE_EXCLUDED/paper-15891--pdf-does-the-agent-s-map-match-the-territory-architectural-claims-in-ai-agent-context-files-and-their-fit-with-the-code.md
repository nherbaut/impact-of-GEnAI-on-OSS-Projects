---
schema: paper-monitor/paper/v1
paper_id: 15891
record_type: PAPER
bibliography:
  title: '[PDF] Does the Agent''s Map Match the Territory? Architectural Claims in AI Agent Context Files and Their Fit with
    the Code'
  authors: Bachan Ghimire, Daniela Damian
  abstract: 'AI coding agents start every session without memory of how a system is built. Developers fill this gap with context
    files, such as CLAUDE.md and AGENTS.md. Agents treat these files as true, so it matters whether they match the code. We
    study two kinds of architectural claims that can be checked against a repository: path claims, which name folders and
    files, and dependency rules, which say what may import what. We check 41,090 path claims and 184 dependency rules from
    3,602 context files in 3,346 open-source projects against the code and its history. About 5% of path claims point to paths
    we cannot find, but we estimate that only 2.2% are real errors, similar to READMEs (3.5%). When code moves, 61% of claims
    that became stale are fixed, most in the same commit. Dependency rules behave differently: 33 of 184 (18%) were confirmed
    broken on the day they were written, usually by older code, and nearly all stayed broken. Context files are good maps
    but less reliable rulebooks: their rules often describe the architecture a team wants, not the one it has. In an exploratory
    comparison of 7,480 commits, new rule breaks were rare. Agent-assisted commits broke rules about 1.8 times as often as
    other commits (0.29% vs. 0.16%), but with only 14 breaks this is not significant: an early signal, not evidence of a difference
    or of its absence. We used an LLM with human review at each step, and discuss what this offers and risks for mining studies.'
  publisher: arXiv.org.
  published_on: '2026-11-23'
  doi: null
links:
  source: http://arxiv.org/abs/2611.29916v1
  open_access: https://arxiv.org/abs/2611.29916v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-11-24T09:44:56.646544Z'
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

