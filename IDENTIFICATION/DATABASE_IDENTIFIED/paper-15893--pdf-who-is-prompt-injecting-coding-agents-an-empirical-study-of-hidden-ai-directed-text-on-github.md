---
schema: paper-monitor/paper/v1
paper_id: 15893
record_type: PAPER
bibliography:
  title: '[PDF] Who Is Prompt-Injecting Coding Agents? An Empirical Study of Hidden AI-Directed Text on GitHub'
  authors: Gabi Nakibly, Zvika Babo
  abstract: 'AI coding agents now triage issues, review pull requests and pick up tasks inside GitHub repositories, and to
    do so they read text that anyone with a GitHub account can write. This makes GitHub a prime surface for indirect prompt
    injection, in which instructions embedded in untrusted content steer a model that later processes it. Prior work has demonstrated
    such attacks against agents on GitHub in controlled settings, but how often they occur in practice, who deploys them,
    and for what purpose remain unknown. We present the first large-scale empirical study of AI-directed hidden text on GitHub.
    We analyzed roughly 145 million issues, pull requests, comments and README files, detected text that GitHub does not render
    to a human reader but that an agent receives in full, and filtered it with a two-stage LLM classification, a template
    provenance check and an exhaustive manual review. We identify 2,281 validated findings in issues, pull requests and comments
    (16 per million items), and AI-directed hidden text in the READMEs of 107 repositories. We find a heterogeneous ecosystem
    of four uses: attacks on other parties'' agents, defensive text that restricts agents, content override that steers what
    they write, and first-party orchestration, in which projects coordinate their own agents through hidden markers. Attacks
    are rare (about one in 3.3 million items) but aimed at maintainers'' own triage, review and CI agents. Orchestration accounts
    for two thirds of the findings in issues, pull requests and comments, grew fivefold in four months, and forms a control
    channel that anyone who can comment can imitate. Replayed offline against five models we tested, the attacks succeed against
    one small, fast model in 19% of cases, and against none once HTML comments are stripped. We release our detection tool
    and every finding.'
  publisher: arXiv.org.
  published_on: '2026-11-21'
  doi: null
links:
  source: http://arxiv.org/abs/2611.28763v1
  open_access: https://arxiv.org/abs/2611.28763v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-11-24T09:44:56.646544Z'
workflow:
  state:
    id: IDENTIFICATION/DATABASE_IDENTIFIED
    label: Database identified
    prisma_bucket: DATABASE_IDENTIFIED
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

