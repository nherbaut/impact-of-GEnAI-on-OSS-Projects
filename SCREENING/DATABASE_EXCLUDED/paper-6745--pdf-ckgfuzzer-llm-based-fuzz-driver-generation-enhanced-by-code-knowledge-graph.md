---
schema: paper-monitor/paper/v1
paper_id: 6745
record_type: PAPER
bibliography:
  title: '[PDF] CKGFuzzer: LLM-Based Fuzz Driver Generation Enhanced By Code Knowledge Graph'
  authors: Hao Xu, Wei Ma, T. Zhou, Yanjie Zhao, Kai Chen, Qiang Hu, Yang Liu, Haoyu Wang
  abstract: In recent years, the programming capabilities of large language models (LLMs) have garnered significant attention.
    Fuzz testing, a highly effective technique, plays a key role in enhancing software reliability and detecting vulnerabilities.
    However, traditional fuzz testing tools rely on manually crafted fuzz drivers, which can limit both testing efficiency
    and effectiveness. To address this challenge, we propose an automated fuzz testing method driven by a code knowledge graph
    and powered by an LLM-based intelligent agent system, referred to as CKGFuzzer. We approach fuzz driver creation as a
    code generation task, leveraging the knowledge graph of the code repository to automate the generation process within
    the fuzzing loop, while continuously refining both the fuzz driver and input seeds. The code knowledge graph is constructed
    through interprocedural program analysis, where each node in the graph represents a code entity, such as a function or
    a file. The knowledge graph-enhanced CKGFuzzer not only effectively resolves compilation errors in fuzz drivers and generates
    input seeds tailored to specific API usage scenarios, but also analyzes fuzz driver crash reports, assisting developers
    in improving code quality. By querying the knowledge graph of the code repository and learning from API usage scenarios,
    we can better identify testing targets and understand the specific purpose of each fuzz driver. We evaluated our approach
    using eight open-source software projects. The experimental results indicate that CKGFuzzer achieved an average improvement
    of 8.73% in code coverage compared to state-of-the-art techniques. Additionally, CKGFuzzer reduced the manual review workload
    in crash case analysis by 84.4% and successfully detected 11 real bugs (including nine previously unreported bugs) across
    the tested libraries. Our research enhances the overall performance of fuzz testing by refining fuzz driver generation
    strategies and input seed analysis, offering a more effective solution for vulnerability remediation and software quality
    improvement.
  publisher: Proceedings International Conference on Software Engineering.
  published_on: '2025-04-27'
  doi: null
links:
  source: http://arxiv.org/abs/2411.11532v3
  open_access: https://arxiv.org/abs/2411.11532v3
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

