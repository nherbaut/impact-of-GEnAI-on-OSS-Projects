---
schema: paper-monitor/paper/v1
paper_id: 10818
record_type: PAPER
bibliography:
  title: '[PDF] Scanning the Harness: An Empirical Study of Supply-Chain Defects in AI Coding-Agent Configurations'
  authors: Benjamin Kapner, Carmel Soceanu, Alicia Petrunin, Hofni Gartner
  abstract: 'AI coding agents such as Claude Code, Cursor, GitHub Copilot, and OpenAI Codex are configured through artifacts
    developers write and share: instruction files, skills, hooks, MCP server declarations, subagents. This harness is a dependency
    layer installed from marketplaces and public repositories, running with the developer''s privileges, with no lockfile,
    no install-time check, and no vocabulary for what a component may do. We study it over 3,171 public GitHub repositories:
    2,660 setups that assemble two or more component types and 511 published skill collections. We measure only rules decidable
    from bytes whose consequence is a security exposure, a configuration that cannot work, or a departure from the Agent Skills
    specification, and validate every finding before it counts: an independent implementation re-derives it from the repository
    at its pinned commit, a language-model adjudicator with a released prompt rules on every disagreement, and a second independent
    model session re-checks every counted pair. Three security classes survive: 9.8% of setups install an MCP server with
    no version pinned, 3.1% pre-approve arbitrary execution behind a scoped-looking grant such as Bash(python:*), and 3.8%
    carry a skill that pre-approves the shell for whoever installs it. In total 16.0% of setups carry a security defect and
    16.7% a confirmed defect of any kind, against a raw scanner rate of 25.5% on the same rules; the third class ships inside
    3.7% of collections, where a marketplace scan can see it. Rules that compare two files detect differences that are usually
    intended and are reported as observations. No credential-exfiltration path was confirmed. The instrument, corpus manifest,
    prompt, and every verdict are released.'
  publisher: arXiv.org.
  published_on: '2026-09-07'
  doi: null
links:
  source: http://arxiv.org/abs/2609.07360v1
  open_access: https://arxiv.org/abs/2609.07360v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-09-10T23:36:38.008185Z'
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

