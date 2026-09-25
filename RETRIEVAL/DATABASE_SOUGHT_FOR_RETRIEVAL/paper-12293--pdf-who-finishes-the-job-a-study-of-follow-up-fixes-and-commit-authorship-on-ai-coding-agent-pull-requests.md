---
schema: paper-monitor/paper/v1
paper_id: 12293
record_type: PAPER
bibliography:
  title: '[PDF] Who Finishes the Job? A Study of Follow-Up Fixes and Commit Authorship on AI Coding Agent Pull Requests'
  authors: Wannita Takerngsaksiri, Nhat Duong, Scott Barnett
  abstract: AI coding agents now author a large share of pull requests (PRs) merged into popular open-source projects. A merged
    agent PR is usually considered finished work; yet, prior studies have reported issues in agent code after the merge (e.g.,
    code smells and static-analysis issues). However, little is known about how often a merged agent PR is fixed afterward,
    and who actually authors the fixing. In this paper, we follow 6,774 merged agent PRs across five AI coding agents (OpenAI
    Codex, GitHub Copilot, Devin, Cursor, and Claude Code) from the AIDev-pop dataset (open-source repositories with at least
    500 stars) into their follow-up fixes, against a baseline of 5,044 contemporaneous human PRs from the same repositories.
    We link each merge to its candidate fixes, verify every candidate with human annotators and an LLM judge that matches
    human-level agreement (binary Cohen's Kappa=0.78$ against a human-human K=0.77$, Direct-fix precision 90%), and attribute
    the fixing work at the PR and the commit level. Our findings show that (1) merged agent PRs attract verified fixes at
    1.62 times the odds of merged human PRs in the same repositories over the same period of time; (2) 69.6% of verified fixes
    in agent merges come from the same agent; and (3) 76.4% of the verified fix PRs are agent-authored throughout all commits.
    These results show that agents currently largely finish their own job, but their merges still require fixing more often
    than human merges.
  publisher: arXiv.org.
  published_on: '2026-09-22'
  doi: null
links:
  source: http://arxiv.org/abs/2609.26847v1
  open_access: https://arxiv.org/abs/2609.26847v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-09-24T11:08:32.777514Z'
workflow:
  state:
    id: RETRIEVAL/DATABASE_SOUGHT_FOR_RETRIEVAL
    label: Database sought for retrieval
    prisma_bucket: DATABASE_SOUGHT_FOR_RETRIEVAL
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

