---
schema: paper-monitor/paper/v1
paper_id: 7605
record_type: PAPER
bibliography:
  title: '[PDF] RepoMind: Enhancing Repository-Level Code Generation via LLM Reasoning over Structured Repository Documentation'
  authors: Songwen Gong, Mengzhen Wang, Jiexin Wang, Yi Cai
  abstract: Repository-level code generation aims to generate target code conditioned on the context of the specified repository.
    Existing approaches generally adopt the Retrieval-Augmented Generation (RAG) framework to retrieve relevant contextual
    information from the repository, thereby mitigating the challenge of long context windows. However, these methods typically
    struggle to identify truly relevant information for the current generation requirement, and they generally overlook the
    imperative need for understanding the repository-level code structure during the retrieval process. To address these issues,
    we propose RepoMind, a novel framework that advances repository-level code generation by leveraging a repository documentation
    library and LLM reasoning capabilities for API retrieval. Specifically, RepoMind first introduces the RepoDocs Agent.
    This component constructs multi-granularity, hierarchical structural documentation in a bottom-up manner, providing LLMs
    with a high-quality knowledge base for understanding repository functionality and structure. Built upon this hierarchical
    knowledge base, RepoMind further integrates the Reasoning-Retrieval Agent. This agent mimics human developer patterns
    by utilizing the repository documentation for layer-by-layer exploration, and ultimately precisely localizes the relevant
    API sets. Finally, the framework combines the functionally relevant API set retrieved via LLM reasoning with the semantically
    similar API set retrieved by the vector retriever, utilizing this hybrid context to boost code generation performance.
    Evaluation on widely-used repository-level code generation benchmarks, CoderEval and DevEval, demonstrates that RepoMind
    surpasses state-of-the-art methods, achieving up to a 13.50% relative improvement in Pass@1 scores. The open-source code
    will be released at https://github.com/ABigTrouble/RepoMind.
  publisher: Proceedings 2026 IEEE ACM 34th International Conference on Program Comprehension Icpc 2026.
  published_on: '2026-04-12'
  doi: 10.1145/3794763.3794823
links:
  source: https://doi.org/10.1145/3794763.3794823
  open_access: https://doi.org/10.1145/3794763.3794823
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-08-19T14:01:02.452399Z'
workflow:
  state:
    id: SCREENING/DATABASE_EXCLUDED
    label: Database excluded at screening
    prisma_bucket: DATABASE_SCREENING_EXCLUDED
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

