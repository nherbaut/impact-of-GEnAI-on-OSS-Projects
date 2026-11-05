---
schema: paper-monitor/paper/v1
paper_id: 7358
record_type: PAPER
bibliography:
  title: '[PDF] Maintenance Signals in AI-Assisted GitHub Repositories: Evidence from GenAI Adopters'
  authors: Rikuto Tsuchida, Youmei Fan, Kazumasa Shimari, Raula Gaikovina Kula, Gema Rodríguez-Pérez, Kenichi Matsumoto
  abstract: Generative artificial intelligence (GenAI) can reduce code-generation effort, but it may shift work to documentation,
    validation, debugging, and maintenance. We study observable maintenance-cost signals among GenAI adopters on GitHub by
    analyzing 622 users who publicly signal adoption, 179 repositories with visible AI-assistance configuration files, 179
    matched traditional repositories, and 248 issues created in AI-assisted repositories. AI-assisted repositories span diverse
    project types and contain longer README files with more headers and code blocks, while traditional repositories contain
    more external URLs. Issues concerning GenAI technology often involve external dependencies, such as API rate limits and
    reliance on GenAI provider APIs. These findings suggest that AI assistance shifts maintenance costs toward verifying generated
    content, managing external AI dependencies, and validating AI-specific behavior.
  publisher: arXiv.org.
  published_on: '2026-07-23'
  doi: null
links:
  source: http://arxiv.org/abs/2607.21079v1
  open_access: https://arxiv.org/abs/2607.21079v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-07-24T07:41:32.829200Z'
workflow:
  state:
    id: INCLUDED/DATABASE_REVIEWED
    label: Database Reviewed
    prisma_bucket: DATABASE_INCLUDED
  tags:
  - arxiv
  eligibility:
    exclusion: null
    inclusion:
      criteria:
      - id: ADDRESSES_TARGET_TOPIC
        label: Addresses the target topic
      - id: DIRECTLY_EVALUATES_TARGET
        label: Directly evaluates the target phenomenon
      - id: REPORTS_PRIMARY_DATA
        label: Reports primary data
      - id: CONTAINS_EMPIRICAL_EVALUATION
        label: Contains empirical evaluation
      - id: ACCEPTABLE_STUDY_DESIGN
        label: Acceptable study design
      - id: SUFFICIENT_METHOD_DETAIL
        label: Sufficient method detail
files:
  pdf:
    available: true
    name: paper-7358--pdf-maintenance-signals-in-ai-assisted-github-repositories-evidence-from-genai-adopters.pdf
    original_name: 2607.21079v1.pdf
---

## OpenAI structured abstract

_Generated 2026-09-14T13:18:01.819162684Z_

INTRODUCTION: Generative AI (GenAI) may lower code-generation effort but shift work to documentation, validation, debugging, and maintenance. This study investigates observable maintenance-cost signals among GitHub developers who publicly signal GenAI adoption.

METHODS: Public GitHub data (REST/GraphQL APIs) were collected May 25–Aug 14, 2025. Adopters were identified via profile keywords (“AI Agent”, “AI App”, “Vibe Coding”) with activity filters, yielding 622 users. Repositories owned by these users were filtered for recent activity; AI-assisted repositories were detected by the presence (including via .gitignore) of configuration files for GenAI agents or Model Context Protocol (MCP) servers. Each of 179 AI-assisted repositories was matched by commit count to a traditional repository (n=179). Repository types were classified using Zanartu et al.’s five-category taxonomy. README characteristics (length, header/code/image/URL densities per 1k chars, license presence) were compared using Mann–Whitney U tests with Bonferroni correction and Cliff’s delta; category distributions were compared by Chi-square. For maintenance signals, 248 issues authored by the adopters in AI-assisted repositories were labeled as GenAI-related or Non-GenAI-related and classified by Issue Type (Bug/Enhancement/Other) and Outcome (External, Internal, UI/UX, Developer Experience, Environment, Documentation).

RESULTS: Repository categories did not differ significantly between AI-assisted and traditional repositories (Chi-square p=0.240). AI-assisted repositories had longer READMEs and higher densities of H1 headers and code blocks (small effect sizes), while traditional repositories had higher URL density; image density and license presence showed no significant differences after correction. Across 248 adopter-authored issues, Enhancements predominated in both groups. GenAI-related issues were more concentrated in External outcomes (e.g., provider API rate limits, quotas), whereas Non-GenAI-related issues more often involved UI/UX. After removing a dominant contributor, the External concentration for GenAI-related issues persisted (Fisher’s exact p=0.025), while the UI/UX difference did not.

DISCUSSION: Visible GenAI assistance appears across diverse project types rather than a single domain. Maintenance costs appear to shift toward verifying generated content, managing external AI dependencies (e.g., rate limits, API availability), and validating AI-specific behavior (e.g., output parsing, multimodal logic). While GenAI assistance is associated with more structured README documentation, curating reliable external resources still requires human judgment.