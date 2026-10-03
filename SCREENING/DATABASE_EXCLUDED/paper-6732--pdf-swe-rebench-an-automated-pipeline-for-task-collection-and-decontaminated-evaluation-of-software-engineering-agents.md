---
schema: paper-monitor/paper/v1
paper_id: 6732
record_type: PAPER
bibliography:
  title: '[PDF] SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering
    Agents'
  authors: Ibragim Badertdinov, Alexander Golubev, Maksim Nekrashevich, Anton Shevtsov, Simon Karasik, Andrei Andriushchenko,
    Maria Trofimova, Daria Litvintseva, Boris Yangel
  abstract: LLM-based agents have shown promising capabilities in a growing range of software engineering (SWE) tasks. However,
    advancing this field faces two critical challenges. First, high-quality training data is scarce, especially data that
    reflects real-world SWE scenarios, where agents must interact with development environments, execute code and adapt behavior
    based on the outcomes of their actions. Existing datasets are either limited to one-shot code generation or comprise small,
    manually curated collections of interactive tasks, lacking both scale and diversity. Second, the lack of fresh interactive
    SWE tasks affects evaluation of rapidly improving models, as static benchmarks quickly become outdated due to contamination
    issues. To address these limitations, we introduce a novel, automated, and scalable pipeline to continuously extract real-world
    interactive SWE tasks from diverse GitHub repositories. Using this pipeline, we construct SWE-rebench, a public dataset
    comprising over 21,000 interactive Python-based SWE tasks, suitable for reinforcement learning of SWE agents at scale.
    Additionally, we use continuous supply of fresh tasks collected using SWE-rebench methodology to build a contamination-free
    benchmark for agentic software engineering. We compare results of various LLMs on this benchmark to results on SWE-bench
    Verified and show that performance of some language models might be inflated due to contamination issues.
  publisher: arXiv.org.
  published_on: '2025-05-26'
  doi: null
links:
  source: http://arxiv.org/abs/2505.20411v2
  open_access: https://arxiv.org/abs/2505.20411v2
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

