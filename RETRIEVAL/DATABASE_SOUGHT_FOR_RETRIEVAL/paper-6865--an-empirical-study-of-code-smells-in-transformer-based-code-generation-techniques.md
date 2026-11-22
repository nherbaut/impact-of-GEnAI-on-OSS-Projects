---
schema: paper-monitor/paper/v1
paper_id: 6865
record_type: PAPER
bibliography:
  title: An Empirical Study of Code Smells in Transformer-based Code Generation Techniques
  authors: Mohammed Latif Siddiq, Shafayat Hossain Majumder, Maisha R. Mim, Sourov Jajodia, Joanna C. S. Santos
  abstract: Prior works have developed transformer-based language learning models to automatically generate source code for
    a task without compilation errors. The datasets used to train these techniques include samples from open source projects
    which may not be free of security flaws, code smells, and violations of standard coding practices. Therefore, we investigate
    to what extent code smells are present in the datasets of coding generation techniques and verify whether they leak into
    the output of these techniques. To conduct this study, we used Pylint and Bandit to detect code smells and security smells
    in three widely used training sets (CodeXGlue, APPS, and Code Clippy). We observed that Pylint caught 264 code smell types,
    whereas Bandit located 44 security smell types in these three datasets used for training code generation techniques. By
    analyzing the output from ten different configurations of the open-source fine-tuned transformer-based GPT-Neo 125M parameters
    model, we observed that this model leaked the smells and non-standard practices to the generated source code. When analyzing
    GitHub Copilot's suggestions, a closed source code generation tool, we observed that it contained 18 types of code smells,
    including substandard coding patterns and 2 security smell types.
  publisher: Proceedings 2022 IEEE 22nd International Working Conference on Source Code Analysis and Manipulation Scam 2022
  published_on: '2022-10-01'
  doi: 10.1109/scam55253.2022.00014
links:
  source: https://doi.org/10.1109/scam55253.2022.00014
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

