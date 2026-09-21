---
schema: paper-monitor/paper/v1
paper_id: 6730
record_type: PAPER
bibliography:
  title: '[PDF] RepoMaster: Autonomous Exploration and Understanding of GitHub Repositories for Complex Task Solving'
  authors: Huacan Wang, Ziyi Ni, Shuo Zhang, Shuo Lu, Sen Hu, Ziyang He, Chen Hu, Jiaye Lin, Yifu Guo, Ronghao Chen, Xin Li,
    Daxin Jiang, Yuntao Du, Pin Lyu
  abstract: 'The ultimate goal of code agents is to solve complex tasks autonomously. Although large language models (LLMs)
    have made substantial progress in code generation, real-world tasks typically demand full-fledged code repositories rather
    than simple scripts. Building such repositories from scratch remains a major challenge. Fortunately, GitHub hosts a vast,
    evolving collection of open-source repositories, which developers frequently reuse as modular components for complex tasks.
    Yet, existing frameworks like OpenHands and SWE-Agent still struggle to effectively leverage these valuable resources.
    Relying solely on README files provides insufficient guidance, and deeper exploration reveals two core obstacles: overwhelming
    information and tangled dependencies of repositories, both constrained by the limited context windows of current LLMs.
    To tackle these issues, we propose RepoMaster, an autonomous agent framework designed to explore and reuse GitHub repositories
    for solving complex tasks. For efficient understanding, RepoMaster constructs function-call graphs, module-dependency
    graphs, and hierarchical code trees to identify essential components, providing only identified core elements to the LLMs
    rather than the entire repository. During autonomous execution, it progressively explores related components using our
    exploration tools and prunes information to optimize context usage. Evaluated on the adjusted MLE-bench, RepoMaster achieves
    a 110% relative boost in valid submissions over the strongest baseline OpenHands. On our newly released GitTaskBench,
    RepoMaster lifts the task-pass rate from 40.7% to 62.9% while reducing token usage by 95%. Our code and demonstration
    materials are publicly available at https://github.com/QuantaAlpha/RepoMaster.'
  publisher: arXiv.org.
  published_on: '2025-05-27'
  doi: null
links:
  source: http://arxiv.org/abs/2505.21577v3
  open_access: https://arxiv.org/abs/2505.21577v3
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-06-30T13:29:23.865282Z'
workflow:
  state:
    id: RETRIEVAL/DATABASE_SOUGHT_FOR_RETRIEVAL
    label: Database sought for retrieval
    prisma_bucket: DATABASE_SOUGHT_FOR_RETRIEVAL
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

