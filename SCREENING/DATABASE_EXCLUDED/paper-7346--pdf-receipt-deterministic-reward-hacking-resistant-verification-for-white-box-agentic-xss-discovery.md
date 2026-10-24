---
schema: paper-monitor/paper/v1
paper_id: 7346
record_type: PAPER
bibliography:
  title: '[PDF] RECEIPT: Deterministic, Reward-Hacking-Resistant Verification for White-Box Agentic XSS Discovery'
  authors: Muxi Lyu, Karen Shieh, Yiwei Hou, Hao Wang, Koushik Sen, David Wagner
  abstract: 'Cross-Site Scripting (XSS) remains one of the most prevalent and damaging classes of web vulnerabilities. LLM-based
    coding agents offer a promising approach to XSS discovery by combining source-code reasoning with interactive testing
    against a running application. However, a coding agent''s claims cannot be trusted on their own. We characterize three
    reward-hacking behaviors in white-box agentic XSS discovery and propose three requirements that an ideal verifier should
    meet. We present RECEIPT, a verification framework that makes agent-reported XSS findings trustworthy by enforcing environment
    isolation, PoC constraints, role separation, and verdict binding. Each confirmation therefore establishes two properties:
    the script runs in a real browser, and the payload was planted under the attacker role and executed in the victim role''s
    browser. This constrained replay procedure makes validation deterministic and reproducible. We evaluate RECEIPT on 95
    real-world web-application targets drawn from popular open-source projects. Within a $20 per-application budget, RECEIPT
    found 24 previously unknown XSS vulnerabilities, 12 of which have already been acknowledged by maintainers after responsible
    disclosure, and recovered the labeled CVE in 36% of known-vulnerability recovery targets. Compared with the same agent
    using self-judgment and with black-box scanners, RECEIPT confirms more real exploits while admitting no false positives.'
  publisher: arXiv.org.
  published_on: '2026-07-20'
  doi: null
links:
  source: http://arxiv.org/abs/2607.18575v1
  open_access: https://arxiv.org/abs/2607.18575v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-07-22T05:41:32.556101Z'
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

