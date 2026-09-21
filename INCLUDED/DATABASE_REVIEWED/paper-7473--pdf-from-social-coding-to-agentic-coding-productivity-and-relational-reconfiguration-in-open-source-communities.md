---
schema: paper-monitor/paper/v1
paper_id: 7473
record_type: PAPER
bibliography:
  title: '[PDF] From Social Coding to Agentic Coding: Productivity and Relational Reconfiguration in Open-Source Communities'
  authors: Mengying Zhou, Yongjie Yin, Yang Chen
  abstract: 'Open-source software communities are a form of digital public infrastructure that not only produces code, but
    also generates public knowledge and interpersonal relationships through visible collaboration. Generative coding agents
    (CAs) are an advanced tool to improve development efficiency while shifting part of activities from public human interaction
    to private human-agent loops. We study this shift using an LLM-based multi-agent simulation initialized with real GitHub
    data from 1,084 active developers and their repository relationships. After a warm-up with historical commits, we branch
    the same community state into parallel No-CA and CA conditions for 4-week simulations. CA introduction increases planned
    and completed tasks by 34.0% and 39.0%, respectively, and reduces median completion time from 45 to 20 minutes. However,
    adoption reaches only 26.0%, and the gains concentrate among developers who are already more active and well connected.
    CAs also restructure task execution pathways. Direct human-human interaction declines from 32.4% to 11.6%, while CA-involved
    modes increase to 57.3%, including 40.3% completed through CA-assisted self-loops. Public knowledge generated under CA
    condition also provides less support for later tasks. On a standardized retrieval benchmark, the CA corpus achieves 22.3%
    knowledge coverage, far below the 81.1% achieved by the real-human corpus, and requires more retrieval steps with a lower
    success rate. These results reveal a productivity-public knowledge tension: coding agents increase technical production,
    but more work shifts to agent-mediated or private loops, leaving public records less useful to future contributors.'
  publisher: arXiv.org.
  published_on: '2026-08-04'
  doi: null
links:
  source: http://arxiv.org/abs/2608.03585v1
  open_access: https://arxiv.org/abs/2608.03585v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-08-05T03:47:35.818277Z'
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
      - id: CLEAR_RESULTS
        label: Clear results
files:
  pdf:
    available: true
    name: paper-7473--pdf-from-social-coding-to-agentic-coding-productivity-and-relational-reconfiguration-in-open-source-communities.pdf
    original_name: 2608.03585v1.pdf
---

paper is really nice, but all the result are from simulating the contribution of ppl on oss projects.
They spend some time demonstrating that their agents show similar feature to the real contributors, then add the possibility for simulated contributor to run agents, then, they show the difference between real and AI assisted contribution.

It's basically more productive, more concentrad than the real deal

## OpenAI structured abstract

_Generated 2026-09-14T08:09:23.107814603Z_

INTRODUCTION: Open-source software (OSS) communities produce code, public knowledge, and relationships through visible collaboration. Generative coding agents (CAs) may increase individual development efficiency while shifting activity from public human–human interaction to private human–agent loops. This study examines how introducing CAs affects community productivity, interaction pathways, and the usefulness of public knowledge.

METHODS: The authors implement an LLM-based multi-agent simulation grounded in real GitHub data for 1,084 continuously active developers connected by repository relationships. After constructing developer-agent profiles from historical activity (2014–2018) and a 4-week warm-up injecting real commits (Jan 21–Feb 18, 2018) for few-shot in-context learning, the same post-warm-up community snapshot is branched into parallel 4-week simulations (Feb 19–Mar 18, 2018): No-CA vs CA available. Developer agents follow a daily Query–Act–Reflect workflow; in the CA branch they can choose CA assistance at the task level. Each condition is run independently three times (primary LLM: DeepSeek V4; robustness: GLM-5.2, Qwen3.7). Outcomes include planned/completed tasks, completion time, adoption and diffusion, interaction modes (human–human vs agent-mediated; cross-developer vs self-loop), and a public-knowledge retrieval benchmark using 8,822 real commits (Mar 19–May 19, 2018) to test coverage, retrieval steps, and success.

RESULTS: Compared with No-CA, CA availability increases planned tasks by 34.0% (3,151→4,221) and completed tasks by 39.0% (2,969→4,128), and reduces median completion time from ~45 to ~20 minutes. Adoption reaches 26.0% by the final day, with CA-assisted commits rising to 65.0% of all commits; gains concentrate among already active and well-connected developers. Task-execution pathways shift: direct human–human interaction drops from 32.4% to 11.6%; CA-involved modes rise to 57.3%, including 40.3% agent-assisted self-loops and 17.0% agent-mediated cross-developer tasks. Relational breadth and short-term repeated interaction remain broadly stable. Public knowledge generated under CA provides substantially lower support for later tasks: on a size-matched corpus, coverage is 22.3%±2.2% vs 81.1% for real-human records; average retrieval steps increase from 2.63 to 8.02; retrieval success falls from 82.3% to 22.3%.

DISCUSSION: Coding agents increase technical production and speed but shift much work into agent-mediated or private loops, reducing visible human–human interaction and the retrievability of public records for subsequent contributors. Benefits and adoption are uneven, amplifying contributions from already active, well-connected developers. The study highlights a productivity–public knowledge tension and suggests evaluating CAs not only for productivity but also for effects on collaboration pathways and community knowledge. Limitations include a fixed developer population, an 8-week observation window, and computational constraints on cross-model comparisons.

## OpenAI structured abstract

_Generated 2026-09-14T08:36:49.241925779Z_

INTRODUCTION: Open-source software (OSS) communities create software, public knowledge, and relationships through visible collaboration. The study investigates how introducing generative coding agents (CAs) affects productivity, interaction pathways, and the usefulness of public records in OSS communities.

METHODS: The authors build an LLM-based multi-agent simulation grounded in real GitHub data for 1,084 continuously active developers connected by observed repository relationships. Agents are initialized with historical profiles and a biographical summary, then warmed up via four weeks of real commits (Jan 22–Feb 18, 2018) for few-shot in-context learning. The shared post-warmup state is branched into parallel 4-week simulations (Feb 19–Mar 18, 2018): No-CA (coding agents unavailable) and CA (coding agent available). Adoption begins with seed developers (broad language coverage and high recent activity), with diffusion via shared repositories; actual use is decided per task. Primary model: DeepSeek V4, with single-run robustness checks using GLM-5.2 and Qwen3.7. Outcomes cover productivity, task-execution modes, interaction indices, and a standardized retrieval benchmark comparing the public-knowledge corpus against subsequent real commits (Mar 19–May 19, 2018).

RESULTS: Compared to No-CA, CA increases planned tasks by 34.0% (3,151→4,221) and completed tasks by 39.0% (2,969→4,128), and reduces median task time from ~45 to 20 minutes. CA awareness and adoption remain limited (awareness 16.0%→36.3%; adoption 6.7%→26.0%), but CA-assisted commits grow from 25.6% to 65.0% of production, concentrating gains among already active, well-connected developers. Task modes shift: direct human–human interaction (HHI) falls from 32.4%±1.4% (No-CA) to 11.6%±2.5% (CA), while CA-involved modes reach 57.3% (AHI 17.0%±1.7%, ASA 40.3%±3.5%). Cross-developer work persists but is frequently agent-mediated (agent mediation among cross-developer tasks: 59.9%±4.4%). Pair-level breadth and short-term continuity remain broadly stable. Public records generated under CA condition provide less support for later tasks: knowledge coverage is 22.3%±2.2% vs 81.1% for the real-human corpus; average retrieval steps rise from 2.63 to 8.02±0.10; retrieval success drops from 82.3% to 22.3%±1.4%. Robustness checks with GLM-5.2 and Qwen3.7 reproduce the directions of these effects.

DISCUSSION: Coding agents increase technical output and speed but shift substantial work into agent-mediated or private human–agent loops, thinning direct human interaction and leaving less reusable public knowledge for future contributors. Adoption concentrates among already active and well-connected developers, suggesting potential participation asymmetries. The study highlights a productivity–public knowledge tension and argues that evaluations of agentic coding should consider effects on collaboration pathways and community knowledge, not only productivity. The authors note limitations including a fixed population, an 8-week observation window, and modeling simplifications, and propose extending simulations to longer horizons and more diverse communities.