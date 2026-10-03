---
schema: paper-monitor/paper/v1
paper_id: 6561
record_type: PAPER
bibliography:
  title: '[PDF] A Deterministic Control Plane for LLM Coding Agents'
  authors: Padmaraj Madatha
  abstract: 'LLM coding harnesses grant agents broad file and shell access, yet the configuration layer that steers them --
    rules files, agent definitions, IDE-specific markdown -- is largely unmanaged. A prevalence study of 10,008 public GitHub
    repositories (n=6,145 agent config files) finds that agent configurations propagate as undeclared shared components: 10.1%
    of tracked paths are SHA-256 exact duplicates across independent repositories (fork-adjusted, threshold-independent),
    with 75.5% of clone pairs crossing organisational boundaries. Two further patterns are indicative: configurations are
    rarely revised (58% single-commit; 0.4 vs 0.6 commits/month age-normalised against CI/CD workflows), and rarely declare
    permission boundaries (<1% of agent configs vs 33% of Actions workflows, n=31 true positives). We propose a deterministic
    control plane above the harness that maps one-to-one to these gaps. Rel(AI)Build treats agent definitions as a managed
    supply chain (SHA-256 content addressing, HMAC-stamped lockfiles, hash-chained audit logs); enforces tiered permissions
    and attack-derived blocklists before LLM invocation; gates feature work through a phase state machine with requirement-to-file-to-test
    traceability; compiles a single canonical definition to seven IDE targets; and detects prompt drift via Jaccard similarity.
    Conformance tests on injected violations confirm each mechanism enforces its stated invariant; developer outcomes remain
    future work. Governance of this layer must be deterministic and tool-agnostic -- not delegated to further LLM orchestration.'
  publisher: arXiv.org.
  published_on: '2026-06-25'
  doi: null
links:
  source: http://arxiv.org/abs/2606.26924v1
  open_access: https://arxiv.org/abs/2606.26924v1
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
    available: true
    name: paper-6561--pdf-a-deterministic-control-plane-for-llm-coding-agents.pdf
    original_name: 2606.26924v1.pdf
---

