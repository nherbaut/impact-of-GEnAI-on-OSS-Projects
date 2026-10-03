---
schema: paper-monitor/paper/v1
paper_id: 6657
record_type: PAPER
bibliography:
  title: 'MCTS-Refined CoT: High-Quality Fine-Tuning Data for LLM-Based Repository Issue Resolution'
  authors: Yibo Wang, Zhihao Peng, Ying Wang, Zhao Wei, Hai Yu, Zhiliang Zhu
  abstract: 'LLMs demonstrate strong performance in automated software engineering, particularly for code generation and issue
    resolution. While proprietary models like GPT-4o achieve high benchmarks scores on SWE-bench, their API dependence, cost,
    and privacy concerns limit adoption. Open-source alternatives offer transparency but underperform in complex tasks, especially
    sub-100B parameter models. Although quality Chain-of-Thought (CoT) data can enhance reasoning, current methods face two
    critical flaws: (1) weak rejection sampling reduces data quality, and (2) inadequate step validation causes error accumulation.
    These limitations lead to flawed reasoning chains that impair LLMs’ ability to learn reliable issue resolution.The paper
    proposes MCTS-REFINE, an enhanced Monte Carlo Tree Search (MCTS)-based algorithm that dynamically validates and optimizes
    intermediate reasoning steps through a rigorous rejection sampling strategy, generating high-quality CoT data to improve
    LLM performance in issue resolution tasks. Key innovations include: (1) augmenting MCTS with a reflection mechanism that
    corrects errors via rejection sampling and refinement, (2) decomposing issue resolution into three subtasks—File Localization,
    Fault Localization, and Patch Generation—each with clear ground-truth criteria, and (3) enforcing a strict sampling protocol
    where intermediate outputs must exactly match verified developer patches, ensuring correctness across reasoning paths.Experiments
    on SWE-bench Lite and SWE-bench Verified demonstrate that LLMs fine-tuned with our CoT dataset achieve substantial improvements
    over baselines. Notably, Qwen2.5-72B-Instruct achieves 28.3%(Lite) and 35.0%(Verified) resolution rates, surpassing SOTA
    baseline SWE-Fixer-Qwen-72B with the same parameter scale, which only reached 24.7%(Lite) and 32.8%(Verified). Given precise
    issue locations as input, our fine-tuned Qwen2.5-72B-Instruct model achieves an impressive issue resolution rate of 43.8%(Verified),
    comparable to the performance of Deepseek-v3. We open-source our MCTS-REFINE framework, CoT dataset, and fine-tuned models
    to advance research in AI-driven software engineering.'
  publisher: Proceedings 2025 40th IEEE ACM International Conference on Automated Software Engineering Ase 2025
  published_on: '2025-11-16'
  doi: 10.1109/ase63991.2025.00154
links:
  source: https://doi.org/10.1109/ase63991.2025.00154
  open_access: null
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

