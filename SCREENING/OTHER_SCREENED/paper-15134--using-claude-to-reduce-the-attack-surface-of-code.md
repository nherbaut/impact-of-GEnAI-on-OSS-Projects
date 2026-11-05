---
schema: paper-monitor/paper/v1
paper_id: 15134
record_type: PAPER
bibliography:
  title: Using Claude to reduce the attack surface of code
  authors: null
  abstract: 'rq1 — GenAI adoption, work and contributor trajectories in OSS Relevance reason: The article applies Claude to
    open-source codebases and describes fixes worked through with maintainers, but does not examine GenAI adoption patterns,
    collective work, contributor participation or trajectories. LLM relevance judgment: 0.18 (rejected; threshold 0.4) AI
    assessment: openai / gpt-6-luna · prompt objective-batch-fulltext-v1:7109572b2ecd86acd727ff67e38671c9 rq2 — Responsibility,
    trust, learning and belonging under GenAI use Relevance reason: The article reports Claude analyzing OSS code and maintainers
    reviewing fixes, but does not examine how AI use affects contributor responsibility, trust, learning, belonging, or shared
    knowledge. LLM relevance judgment: 0.16 (rejected; threshold 0.4) AI assessment: openai / gpt-6-luna · prompt objective-batch-fulltext-v1:7109572b2ecd86acd727ff67e38671c9
    rq3 — Sustainability trade-offs, dependencies and non-substitutable limits Relevance reason: It reports a concrete technical-quality
    benefit from using Claude on OSS, but does not assess sustainability trade-offs, resource demand, provider dependence,
    community continuity or non-substitutable limits. Summary: The article describes applying Claude to 25 open-source projects,
    covering more than five million lines of code, to identify security-relevant attack surfaces. The authors report that
    Claude found 493 issues, including unintentionally reachable code and configuration combinations that weakened security
    controls. An OpenSSH case study describes reducing unauthenticated reachability through changes reviewed with maintainers
    and shipped in later releases. The article also outlines a reusable analysis workflow involving code inventories, dynamic
    traces and test suites. These are reported technical-security findings and methods, not measurements of broader sustainability
    outcomes. The article does not quantify energy, water, hardware or token use; compare hosted and local configurations;
    or assess effects on maintainer workload, project continuity or provider dependence. Its relevance is therefore limited
    to one technical-quality dimension of OSS, rather than the sustainability trade-offs and limits in the objective. Contribution:
    Provides a specific example of Claude being used to identify and help remediate security weaknesses in OSS, with a described
    verification workflow. This informs the technical-quality dimension, but not the broader sustainability hypothesis. Applicability:
    The case offers context for assessing whether GenAI configurations can improve OSS technical quality. Its workflow—inventorying
    entry points, validating findings with dynamic traces, and checking changes against tests—could inform technical evaluations.
    It does not establish the environmental or social costs of that configuration, nor whether the results generalize across
    projects. Novelty: The article presents its research as initial work and describes a reusable skill, but literature-wide
    novelty cannot be established from this article alone. Limitations: There is no sustainability framework or accounting
    of absolute resource use, token costs, maintainer labor, community continuity, or proprietary dependence. The article
    does not provide a comparison with non-AI analysis or enough project-selection detail to establish generalizability. Security
    improvements do not by themselves demonstrate overall sustainability. Uncertainty: The article reports results from 25
    projects and describes particular fixes, but uncertainty remains about project representativeness and how broadly the
    workflow performs. It provides no evidence about lifecycle resource impacts or whether the reported technical gains outweigh
    other costs. LLM relevance judgment: 0.43 (accepted; threshold 0.4) Claude found 493 issues using the three methods described
    above. Evidence supports: Supports the reported scope of Claude''s security findings, a technical-quality outcome in OSS.
    We analyzed 25 open source pr'
  publisher: 'Hacker News: Newest'
  published_on: '2026-10-21'
  doi: null
links:
  source: https://www.anthropic.com/research/attack-surface-reduction
  open_access: null
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 56
  feed_name: rss-intelligence gray litterature
  discovered_at: '2026-11-02T22:19:09.939593Z'
workflow:
  state:
    id: SCREENING/OTHER_SCREENED
    label: Other screened
    prisma_bucket: OTHER_SCREENED
  tags:
  - gray-lit
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

