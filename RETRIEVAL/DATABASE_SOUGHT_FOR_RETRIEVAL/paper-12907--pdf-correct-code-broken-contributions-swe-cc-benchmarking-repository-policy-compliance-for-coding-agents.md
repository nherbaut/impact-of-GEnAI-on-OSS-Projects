---
schema: paper-monitor/paper/v1
paper_id: 12907
record_type: PAPER
bibliography:
  title: '[PDF] Correct Code, Broken Contributions? SWE-CC: Benchmarking Repository Policy Compliance for Coding Agents'
  authors: Hai Dang Truong, Rayner Goh, Thanh Le-Cong, Yintong Huo
  abstract: 'Autonomous coding agents now resolve a substantial share of real-world GitHub issues. However, passing functional
    tests differs fundamentally from producing a high-quality contribution acceptable for merging. Mature open-source projects
    publish repository-specific contribution policies, spanning style, git, testing workflows, to ensure code quality and
    long-term maintainability. Because existing benchmarks evaluate patches solely on unit tests, agent compliance with repository
    governance remains unknown. In this paper, we introduce SWE-CC, a benchmark evaluating code and process compliance in
    autonomous software engineering. We develop a semi-automated pipeline that converts developer documentation across 12
    open-source repositories into 823 machine-checkable atomic policies. SWE-CC introduces two features: 1) lightweight, deterministic
    checker functions that represent each policy, 2) a comprehensive auditing mechanism that inspects both agent runtime behaviors
    and final deliverables. We evaluate the compliance of agent workflows in 500 end-to-end software contribution tasks extended
    from SWE-bench Verified. Our evaluation of four LLMs under two agent scaffolds shows that modern agents suffer from coding
    compliance issues: although agents produce functionally correct patches, they still violate 43.1 percent of applicable
    project policies, with nearly half of all violations occurring during intermediate execution steps. These results show
    that functional correctness does not guarantee real-world readiness, highlighting that future software engineering agents
    must reliably conform to repository governance to enable safe and trustworthy deployment.'
  publisher: arXiv.org.
  published_on: '2026-10-05'
  doi: null
links:
  source: http://arxiv.org/abs/2610.06193v1
  open_access: https://arxiv.org/abs/2610.06193v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-06T06:08:22.004886Z'
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

