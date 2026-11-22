---
schema: paper-monitor/paper/v1
paper_id: 15806
record_type: PAPER
bibliography:
  title: Harvard researchers find AI coding agents shifted the bottleneck to code review
  authors: judahmeek
  abstract: 'rq1 — GenAI adoption, work and contributor trajectories in OSS Relevance reason: The article provides firm-level
    evidence about AI adoption, work submitted for review, review workload, and methods for detecting tool use. These findings
    and detection methods may inform OSS research, but the study does not examine OSS projects, community participation, or
    contributor trajectories. Summary: The article describes a working paper analyzing AI coding-agent adoption at 718 firms.
    It reports more code, commits, and pull requests after adoption, but no measurable increase in completed Jira issues and
    a 49 percent rise in time from pull-request submission to merge. Review comments and formal change requests also increased.
    The analysis uses company activity data and employment records, and describes adoption indicators such as AI-related bot
    accounts and “Co-authored-by” signatures. The article notes that use through individual licenses may not be recorded.
    Contribution: It offers comparative firm-level evidence that increased coding activity can coincide with longer review
    queues rather than more completed work. Its discussion of adoption traces and unrecorded individual licenses is relevant
    to designing OSS adoption-detection methods, though not validated in OSS. Applicability: OSS studies could consider measuring
    completed work and review duration alongside commits or pull requests, and could test whether bot accounts or authorship
    metadata identify agent use. The article’s warning about unrecorded individual licenses highlights a possible source of
    missed adoption; these methods would require validation in OSS settings. Novelty: The article reports a particular firm-level
    analysis and adoption-detection approach. Novelty relative to the wider literature cannot be established from this article
    alone. Limitations: The study covers firms, not OSS projects or volunteer communities, and reports no newcomer retention,
    repeat participation, maintainer recruitment, or governance comparisons. Its underlying data are proprietary, individual-license
    use is unrecorded, and the article says the working paper had not completed peer review. Uncertainty: The article reports
    a difference-in-differences analysis and acknowledges potential adoption-timing and measurement limitations. Transfer
    to OSS is uncertain: project workflows, data visibility, and adoption practices may differ, and the article does not test
    the proposed detection methods in OSS. LLM relevance judgment: 0.46 (needs_review; threshold 0.4) Evidence needs review:
    Unmatched quotations were omitted. The paper’s method carries a second lesson, this one for information governance teams.
    The researchers identified agent use partly from traces inside the firms’ own systems, including bot accounts tied to
    AI tools and signatures such as “Co-authored-by” lines in commit messages and pull request descriptions. Evidence supports:
    The article describes concrete traces that could inform, but do not validate, methods for detecting AI use in OSS repository
    data. AI assessment: openai / gpt-6-luna · prompt objective-batch-fulltext-v1:d17fa9b4c3c881e94ab0ca22668e5f3a rq2 — Responsibility,
    trust, learning and belonging under GenAI use Relevance reason: A company engineer’s account links AI-generated outages
    to senior approval rules and review bottlenecks, touching responsibility and authority. It does not study OSS relationships,
    trust, learning, belonging, or shared knowledge. LLM relevance judgment: 0.35 (rejected; threshold 0.4) AI assessment:
    openai / gpt-6-luna · prompt objective-batch-fulltext-v1:d17fa9b4c3c881e94ab0ca22668e5f3a rq3 — Sustainability trade-offs,
    dependencies and non-substitutable limits Relevance reason: The article reports a productivity-versus-review-workload
    trade-off in companies, but does not address OSS viability, environmental or other sustainability dimensions, resource
    demand, or model dependence. LLM relevance judgment: 0.24 (rejected; threshold 0.4) AI assessment: ope'
  publisher: 'Hacker News: Newest'
  published_on: '2026-11-20'
  doi: null
links:
  source: https://complexdiscovery.com/harvard-researchers-find-ai-coding-agents-shifted-the-bottleneck-to-code-review/
  open_access: null
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 56
  feed_name: rss-intelligence gray litterature
  discovered_at: '2026-11-20T22:35:47.006149Z'
workflow:
  state:
    id: IDENTIFICATION/DATABASE_IDENTIFIED
    label: Database identified
    prisma_bucket: DATABASE_IDENTIFIED
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

