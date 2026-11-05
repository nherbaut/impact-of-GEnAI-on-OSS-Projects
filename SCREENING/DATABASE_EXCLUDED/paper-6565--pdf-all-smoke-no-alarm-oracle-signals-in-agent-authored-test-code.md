---
schema: paper-monitor/paper/v1
paper_id: 6565
record_type: PAPER
bibliography:
  title: '[PDF] All Smoke, No Alarm: Oracle Signals in Agent-Authored Test Code'
  authors: Dipayan Banik, Kowshik Chowdhury, Shazibul Islam Shamim
  abstract: 'Software practitioners increasingly use AI coding agents that generate test code alongside production code in
    open source pull requests (PRs). Recent studies report more than 932,000 agent-authored PRs across more than 116,000 repositories,
    yet whether their test files contain meaningful verification logic remains underexplored. Test files lacking explicit
    assertions execute code without verifying behavior, so quality gates based on test-file presence overestimate verification
    strength. The goal of this paper is to help practitioners assess the verification strength of agent-authored patches by
    characterizing oracle signals and their link to merge outcomes and review effort. We conduct an empirical study of 86,156
    test-file patches from 33,596 agent-authored PRs across 2,807 GitHub repositories produced by five coding agents: OpenAI
    Codex, GitHub Copilot, Devin, Cursor, and Claude Code. A qualitative analysis of 384 stratified patches informs a syntactic
    taxonomy of eight oracle signal categories. Applied at scale, 80.2% of test patches contain weak or no explicit oracle
    signals. While raw merge rates are lower for strong-oracle PRs, a regression analysis adjusting for agent, PR size, repository
    popularity, task type, and language shows strong oracles significantly improve merge likelihood (OR = 1.28, p < 0.001).
    Our findings suggest that test file counts substantially overestimate verification strength and that practitioners can
    adopt oracle-aware quality checks to more accurately evaluate agent-authored contributions.'
  publisher: arXiv.org.
  published_on: '2026-06-16'
  doi: null
links:
  source: http://arxiv.org/abs/2606.18168v1
  open_access: https://arxiv.org/abs/2606.18168v1
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

