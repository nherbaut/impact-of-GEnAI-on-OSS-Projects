---
schema: paper-monitor/paper/v1
paper_id: 6807
record_type: PAPER
bibliography:
  title: Evaluating Diverse Large Language Models for Automatic and General Bug Reproduction
  authors: Sungmin Kang, Juyeon Yoon, Nargiz Askarbekkyzy, Shin Yoo
  abstract: Bug reproduction is a critical developer activity that is also challenging to automate, as bug reports are often
    in natural language and thus can be difficult to transform to test cases consistently. As a result, existing techniques
    mostly focused on crash bugs, which are easier to automatically detect and verify. In this work, we overcome this limitation
    by using large language models (LLMs), which have been demonstrated to be adept at natural language processing and code
    generation. By prompting LLMs to generate bug-reproducing tests, and via a post-processing pipeline to automatically identify
    promising generated tests, our proposed technique Libro could successfully reproduce about one-third of all bugs in the
    widely used Defects4J benchmark. Furthermore, our extensive evaluation on 15 LLMs, including 11 open-source LLMs, suggests
    that open-source LLMs also demonstrate substantial potential, with the StarCoder LLM achieving 70% of the reproduction
    performance of the closed-source OpenAI LLM code-davinci-002 on the large Defects4J benchmark, and 90% of performance
    on a held-out bug dataset likely not part of any LLM's training data. In addition, our experiments on LLMs of different
    sizes show that bug reproduction using Libro improves as LLM size increases, providing information as to which LLMs can
    be used with the Libro pipeline.
  publisher: IEEE Transactions on Software Engineering
  published_on: '2024-09-04'
  doi: 10.1109/tse.2024.3450837
links:
  source: https://doi.org/10.1109/tse.2024.3450837
  open_access: null
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

