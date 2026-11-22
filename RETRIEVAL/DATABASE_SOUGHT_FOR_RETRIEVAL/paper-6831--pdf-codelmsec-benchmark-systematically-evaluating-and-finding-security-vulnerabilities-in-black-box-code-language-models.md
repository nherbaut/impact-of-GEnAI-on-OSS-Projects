---
schema: paper-monitor/paper/v1
paper_id: 6831
record_type: PAPER
bibliography:
  title: '[PDF] CodeLMSec Benchmark: Systematically Evaluating and Finding Security Vulnerabilities in Black-Box Code Language
    Models'
  authors: Hossein Hajipour, Keno Haßler, Thorsten Holz, Lea Schönherr, Mario Fritz
  abstract: Large language models (LLMs) for automatic code generation have recently achieved breakthroughs in several programming
    tasks. Their advances in competition-level programming problems have made them an essential pillar of AI-assisted pair
    programming, and tools such as GitHub Copilot have emerged as part of the daily programming workflow used by millions
    of developers. Training data for these models is usually collected from the Internet (e.g., from open-source repositories)
    and is likely to contain faults and security vulnerabilities. This unsanitized training data can cause the language models
    to learn these vulnerabilities and propagate them during the code generation procedure. While these models have been extensively
    evaluated for their ability to produce functionally correct programs, there remains a lack of comprehensive investigations
    and benchmarks addressing the security aspects of these models.In this work, we propose a method to systematically study
    the security issues of code language models to assess their susceptibility to generating vulnerable code. To this end,
    we introduce the first approach to automatically find generated code that contains vulnerabilities in black-box code generation
    models. This involves proposing a novel few-shot prompting approach. We evaluate the effectiveness of our approach by
    examining code language models in generating high-risk security weaknesses. Furthermore, we use our method to create a
    collection of diverse non-secure prompts for various vulnerability scenarios. This dataset serves as a benchmark to evaluate
    and compare the security weaknesses of code language models.
  publisher: Proceedings IEEE Conference on Safe and Trustworthy Machine Learning Satml 2024.
  published_on: '2024-04-09'
  doi: 10.1109/satml59370.2024.00040
links:
  source: https://doi.org/10.1109/satml59370.2024.00040
  open_access: https://figshare.com/articles/conference_contribution/CodeLMSec_Benchmark_Systematically_Evaluating_and_Finding_Security_Vulnerabilities_in_Black-Box_Code_Language_Models/25532854
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

