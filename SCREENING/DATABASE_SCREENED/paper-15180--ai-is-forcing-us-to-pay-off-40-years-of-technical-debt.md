---
schema: paper-monitor/paper/v1
paper_id: 15180
record_type: PAPER
bibliography:
  title: AI is forcing us to pay off 40 years of technical debt
  authors: pseudolus
  abstract: 'rq1 — GenAI adoption, work and contributor trajectories in OSS Relevance reason: The article reports AI-assisted
    security work on open-source PHP and the burden of patching, but gives no evidence about adoption prevalence, community
    work changes, or contributor trajectories. LLM relevance judgment: 0.32 (rejected; threshold 0.4) AI assessment: openai
    / gpt-6-luna · prompt objective-batch-fulltext-v1:d17fa9b4c3c881e94ab0ca22668e5f3a rq2 — Responsibility, trust, learning
    and belonging under GenAI use Relevance reason: The article discusses expert capability and AI-assisted security work,
    but not contributor understanding, interpersonal trust, responsibility practices, learning, or belonging in OSS communities.
    LLM relevance judgment: 0.16 (rejected; threshold 0.4) AI assessment: openai / gpt-6-luna · prompt objective-batch-fulltext-v1:d17fa9b4c3c881e94ab0ca22668e5f3a
    rq3 — Sustainability trade-offs, dependencies and non-substitutable limits Relevance reason: It connects AI-assisted security
    work and proposed model-token donations to the resource and maintenance challenges of widely used open-source software,
    though it does not assess most sustainability dimensions. Summary: The article reports that Calif, with AI tools and OpenAI
    sponsorship, identified an exploitable consequence of a previously reported PHP bug and alerted the PHP Foundation. It
    describes a four-engineer, two-month effort to develop a patch, emphasizing that defenders must close attack paths without
    breaking existing functionality. The article characterizes this work as straining open-source projects that may lack clear
    revenue streams. Suman Jana argues that frontier-lab token donations could help defenders, and expresses optimism about
    LLM-generated patches paired with formally checked proofs. Matthew Green is more pessimistic about whether adequate resources
    will arrive before a major incident. These are reported events and interviewees’ views; the article supplies no measured
    costs, environmental estimates, or comparative outcomes. Contribution: The article illustrates a technical and economic
    sustainability concern: AI can help identify security problems, while fixing them remains demanding, and open-source projects
    may lack clear revenue. Token-budget donations are proposed as support, not evaluated as a durable funding or dependency
    solution. Applicability: The case can inform analysis of security-focused AI use in widely deployed legacy OSS, including
    the distinction between AI-assisted vulnerability discovery and the harder work of safe remediation. It also raises questions
    about whether donated access to frontier models can support under-resourced projects. Novelty: This is a concrete security
    case connecting AI assistance with open-source maintenance and resource constraints. Literature-wide novelty cannot be
    established from this article alone. Limitations: The article gives no measured energy, water, hardware, token, or total
    lifecycle costs; no comparison of hosted and local models; and no quantified effects on maintainers or project continuity.
    It does not establish that donations cause reliance on proprietary providers or show a sustainability envelope or non-substitutable
    limit. Uncertainty: The specific amount and duration of token support, its allocation, and its effect on project viability
    are not reported. Claims about future automation and funding are interviewees’ expectations, not demonstrated outcomes;
    the reported case cannot establish the net or absolute impacts of AI use. LLM relevance judgment: 0.48 (accepted; threshold
    0.4) Maintaining open-source projects that don’t have clear revenue streams despite being widely used is a long-standing
    challenge Evidence supports: The article identifies financial sustainability pressure affecting widely used open-source
    projects. These frontier labs are donating some of their token budgets to look into these bugs Evidence supports: The
    article reports a proposed resource contribution from frontie'
  publisher: 'Hacker News: Newest'
  published_on: '2026-11-04'
  doi: null
links:
  source: https://spectrum.ieee.org/ai-in-cybersecurity-php2shell-vulnerability
  open_access: null
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 56
  feed_name: rss-intelligence gray litterature
  discovered_at: '2026-11-04T22:20:35.005557Z'
workflow:
  state:
    id: SCREENING/DATABASE_SCREENED
    label: Database screened
    prisma_bucket: DATABASE_SCREENED
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

