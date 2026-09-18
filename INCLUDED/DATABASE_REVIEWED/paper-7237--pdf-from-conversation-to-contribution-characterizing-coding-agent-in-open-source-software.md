---
schema: paper-monitor/paper/v1
paper_id: 7237
record_type: PAPER
bibliography:
  title: '[PDF] From Conversation to Contribution: Characterizing Coding Agent in Open-Source Software'
  authors: Zihan Fang, Yueke Zhang, Ningzhi Tang, Collin McMillan, Toby Jia-Jun Li, Yu Huang
  abstract: AI coding assistants such as GitHub Copilot and Cursor have evolved from code-suggestion tools into conversational
    collaborators, enabling vibe-coding workflows in which developers guide AI-generated code through natural-language dialogue.
    Although researchers have increasingly recognized the importance of AI coding agents and begun examining their impact
    on open-source development, a comprehensive understanding of how developers' chat-based interactions with AI relate to
    subsequent open-source development and collaboration remains limited. This hinders efforts to effectively design, evaluate,
    and govern AI-assisted open-source software development. To address this gap, we collected 13,360 AI conversation sessions
    comprising 79,172 user messages from 1,356 OSS repositories, linked them to repository development histories, and complemented
    this analysis with a targeted developer survey. We find heavier AI use in smaller, less mature, and less collaborative
    repositories. After AI adoption, projects tended to show more active contributors and lower contributor concentration
    (p < .001), although communication remained highly concentrated. Code Writing was the dominant chat purpose, and nearly
    all AI chat sessions were followed by subsequent commits. We find no broad deterioration in code-quality signals or pull
    request merging rates. However, developers perceive others' AI-generated code as harder to maintain than their own (p
    = .029) and view AI as lowering barriers to OSS contribution. While most developers (68%) are willing to share their chat,
    concerns remain around appearing incompetent, increasing reviewer burden, and exposing ideas to competitors. These findings
    provide a large-scale empirical characterization of AI-assisted OSS contribution and offer practical insights for designing
    and governing responsible vibe-coding practices in open-source development.
  publisher: arXiv.org.
  published_on: '2026-07-06'
  doi: null
links:
  source: http://arxiv.org/abs/2607.05677v1
  open_access: https://arxiv.org/abs/2607.05677v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-07-08T11:41:21.235128Z'
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
    name: paper-7237--pdf-from-conversation-to-contribution-characterizing-coding-agent-in-open-source-software.pdf
    original_name: 2607.05677v1.pdf
---

## OpenAI structured abstract

_Generated 2026-09-16T08:42:01.541635504Z_

INTRODUCTION: AI coding assistants embedded in IDEs (e.g., Copilot, Cursor, Claude Code) now support conversational, “vibe-coding” workflows. How these chat-based interactions relate to subsequent open-source software (OSS) development and collaboration is not well understood, limiting effective design, evaluation, and governance of AI-assisted OSS.

METHODS: The study mined SpecStory-preserved chat logs from public GitHub repositories and linked them to full repository histories. It collected 13,360 AI chat sessions (79,172 user messages) across 1,356 repositories and assembled repository-level data on commits, files, pull requests (PRs), issues, comments, reviews, and CI checks. After screening and data-access filtering, analyses used 12,108 chat sessions from 1,240 repositories created between April 2013 and March 2026; chat logs spanned September 2024–March 2026. Chat purposes were labeled via an LLM-based multi-label taxonomy. AI adoption timing was defined as the earliest observed AI-chat timestamp in a repository. Interrupted time-series models with repository fixed effects assessed pre/post-adoption dynamics. A developer survey (589 invitations; 25 responses) measured perceptions of benefits/risks, maintainability, disclosure, and appropriate use cases.

RESULTS: AI use concentrated in smaller, less mature, and less collaborative repositories. Post-adoption, monthly commit activity showed a short-lived burst followed by decline. Code Writing dominated chat purposes, and nearly all chat sessions were followed by commits, most commonly source-only or documentation-only. AI-related changes spanned many files but clustered within a few repository modules. No broad deterioration appeared in code-quality signals: bug/fix commit share rose largely due to reduced overall commit volume; test-touching shares and CI outcomes were stable. Activity composition shifted toward PRs, and issue resolution time increased substantially, while PR merge time and merge share did not show significant decline. Contributor participation increased and contributor concentration fell in the main cohort, but communication and review activity remained highly concentrated. Survey respondents reported that AI lowers barriers to OSS contribution, were more concerned about others’ AI-generated code than their own (perceived higher maintenance burden), and most were willing to share chats, citing concerns about reputation, reviewer burden, and idea exposure.

DISCUSSION: Conversational AI is widely used for implementation and related tasks (debugging, inquiry, validation) in OSS, typically leading to follow-up commits without visible context of the underlying AI interaction. While broad code-quality degradation was not observed, issue responsiveness slowed and collaboration remained concentrated. Developers view AI as improving access to participation but worry about maintainability of others’ AI-produced code and the costs of disclosure. Findings suggest opportunities for lightweight transparency (e.g., structured summaries of AI assistance) and governance practices calibrated to change scope and risk rather than blanket policies.