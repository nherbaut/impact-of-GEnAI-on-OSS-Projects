---
schema: paper-monitor/paper/v1
paper_id: 11007
record_type: PAPER
bibliography:
  title: '[PDF] Not All Agents Are Equal: Code Quality and Post-Merge Maintenance Across Five Autonomous Coding Agents in
    the Wild'
  authors: Obada Kraishan
  abstract: 'Autonomous coding agents now open pull requests in public repositories at a scale that was out of reach two years
    ago, yet little is known about what happens to that code after it lands. This paper studies 37,623 provenance-labeled
    pull requests (PRs) from five commercial agents (OpenAI Codex, Devin, GitHub Copilot, Cursor, and Claude Code) and a matched
    human baseline, drawn from 2,807 GitHub repositories between December 2024 and July 2025. We combine the AIDev dataset
    with 58,792 cached GitHub API responses to measure security smells in added code, structural maintainability, post-merge
    churn, revert rates, and human review behavior. Three results stand out. First, quality differences are vendor-specific
    rather than uniform: Codex-authored PRs were reverted about half as often as human PRs (6.1% vs. 11.5%, odds ratio 0.50),
    while Devin PRs were reverted more often (14.5%, odds ratio 1.31). Second, agent code pooled across vendors was less likely
    than human code to contain a security smell (odds ratio 0.63), driven by fewer hardcoded credentials and eval-style constructs.
    Third, review effort concentrates unevenly: Copilot PRs drew the most human reviews and change requests, and Claude Code
    PRs waited the longest for a first human review (median 12.6 hours). All pipeline code, statistical reports, and figures
    are released for replication.'
  publisher: arXiv.org.
  published_on: '2026-09-12'
  doi: null
links:
  source: http://arxiv.org/abs/2609.17598v1
  open_access: https://arxiv.org/abs/2609.17598v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-09-17T09:28:41.123946Z'
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

