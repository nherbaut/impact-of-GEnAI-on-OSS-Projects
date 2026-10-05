---
schema: paper-monitor/paper/v1
paper_id: 12867
record_type: PAPER
bibliography:
  title: '[PDF] Behavior-Driven Development Meets LLMs: Do We Need Them, and Do They Work?'
  authors: Xinyu Shi
  abstract: Behavior-Driven Development (BDD) bridges requirements and test code through human-readable scenarios. However,
    writing and maintaining BDD scenarios and step definitions (glue code) can be challenging and time-consuming. To understand
    whether large language models (LLMs) can effectively support BDD, we conduct an empirical study on 11 open-source Java
    projects. We observe that BDD artifacts expand quickly and undergo frequent modifications. Because each test step is tightly
    coupled to its corresponding glue code, this continuous evolution makes maintenance labor-intensive. In particular, the
    studied projects contain an average of 4,835 test step invocations, and 65.1% of them are updated after their initial
    creation, which forces developers to frequently update the corresponding step definitions. Motivated by this maintenance
    burden, we develop AutoGlue, a retrieval-augmented few-shot prompting framework for glue code generation. To the best
    of our knowledge, AutoGlue is the first approach that automatically generates Java glue code directly from Gherkin steps.
    Our investigation shows that, in the 1-shot setting, AutoGlue achieves a CodeBLEU score of 61.6, which indicates that
    the generated glue code is highly similar to human-written code. Moreover, our preliminary results reveal that incorporating
    project-specific contextual information significantly boosts generation quality, improving the CodeBLEU score by up to
    41%.
  publisher: Proceedings 2026 IEEE ACM 48th International Conference on Software Engineering Companion Proceedings ICSE Companion
    2026.
  published_on: '2026-04-12'
  doi: 10.1145/3774748.3787745
links:
  source: https://doi.org/10.1145/3774748.3787745
  open_access: https://doi.org/10.1145/3774748.3787745
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-03T11:13:22.886791Z'
workflow:
  state:
    id: IDENTIFICATION/DATABASE_IDENTIFIED
    label: Database identified
    prisma_bucket: DATABASE_IDENTIFIED
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

