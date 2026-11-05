---
schema: paper-monitor/paper/v1
paper_id: 15182
record_type: PAPER
bibliography:
  title: '[PDF] Predicting Program Exit Code with LLMs and Programming Language Semantics'
  authors: Lara Marinov, Aditya Thimmaiah, Jayanth Srinivasa, Junyi Jessy Li, Milos Gligoric
  abstract: Large language models (LLMs) have shown proficiency in various software engineering tasks, such as code generation
    and translation. However, a key limitation in their performance may be their (lack of) understanding of programming-language
    semantics. Even when explicit semantics are given, it remains unclear whether LLMs apply those rules or lean on priors
    learned during pre-training instead. We study if LLMs lean on priors or given semantics with a novel task–Program Executability
    Prediction (PrEx)–that asks models to predict whether a program is semantically valid or invalid (and, if invalid, which
    formal rule it violates) given the program’s syntax and operational semantics. Because PrEx requires both valid and invalid
    programs, we build a dataset with systematically generated invalid transformations derived from valid programs. We evaluate
    open-source coding LLMs under two semantic formalisms and two semantic shifts across Human-Written, LLM-Translated, and
    Fuzzer-Generated program splits. Our findings show that LLMs lean on pre-training priors rather than systematically applying
    the given rules, performing especially poorly on modified semantics and degrading further as program complexity increases.
    PrEx is available at https://github.com/EngineeringSoftware/prex.
  publisher: Lmpl 2026 Proceedings of the 2nd ACM SIGPLAN International Workshop on Language Models and Programming Languages
    Co Located with Issta Splash 2026.
  published_on: '2026-10-02'
  doi: 10.1145/3843750.3843842
links:
  source: https://doi.org/10.1145/3843750.3843842
  open_access: https://dl.acm.org/doi/pdf/10.1145/3843750.3843842?download=true
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-11-05T01:43:35.005770Z'
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

