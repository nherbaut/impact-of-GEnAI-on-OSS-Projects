---
schema: paper-monitor/paper/v1
paper_id: 6610
record_type: PAPER
bibliography:
  title: '[PDF] Can Developers rely on LLMs for Secure IaC Development?'
  authors: Ehsan Firouzi, Shardul Bhatt, Mohammad Ghafari
  abstract: We investigated the capabilities of GPT-4o and Gemini 2.0 Flash for secure Infrastructure as Code (IaC) development.
    For security smell detection, on the Stack Overflow dataset, which primarily contains small, simplified code snippets,
    the models detected at least 71% of security smells when prompted to analyze code from a security perspective (general
    prompt). With a guided prompt (adding clear, step-by-step instructions), this increased to 78%.In GitHub repositories,
    which contain complete, real-world project scripts, a general prompt was less effective, leaving more than half of the
    smells undetected. However, with the guided prompt, the models uncovered at least 67% of the smells. For secure code generation,
    we prompted LLMs with 89 vulnerable synthetic scenarios and observed that only 7% of the generated scripts were secure.
    Adding an explicit instruction to generate secure code increased GPT secure output rate to 17%, while Gemini changed little
    (8%). These results highlight the need for further research to improve LLMs' capabilities in assisting developers with
    secure IaC development.
  publisher: arXiv.org.
  published_on: '2026-02-03'
  doi: null
links:
  source: http://arxiv.org/abs/2602.03648v1
  open_access: https://arxiv.org/abs/2602.03648v1
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

