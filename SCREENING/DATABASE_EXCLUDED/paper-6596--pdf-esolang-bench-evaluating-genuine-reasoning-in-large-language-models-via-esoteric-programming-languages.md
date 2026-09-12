---
schema: paper-monitor/paper/v1
paper_id: 6596
record_type: PAPER
bibliography:
  title: '[PDF] EsoLang-Bench: Evaluating Genuine Reasoning in Large Language Models via Esoteric Programming Languages'
  authors: Aman Sharma, Paras Chopra
  abstract: 'Large language models achieve near-ceiling performance on code generation benchmarks, yet most of the programming
    languages used by popular benchmarks such as SWE-bench and HumanEval (e.g. Python, JavaScript) are squarely in-distribution.
    They appear at scale in pre-training corpora and are heavily reinforced during post-training. To study LLM performance
    on unfamiliar programming languages, we introduce EsoLang-Bench, a benchmark using five esoteric programming languages
    (Brainfuck, Befunge-98, Whitespace, Unlambda, and Shakespeare). All five of our chosen esoteric languages are Turing-complete,
    so the same algorithmic problems that are solvable in Python or JavaScript are in principle solvable in each of them.
    Yet, they are unfamiliar to LLMs which makes them a good proxy for evaluating out-of-distribution performance. The unfamiliarity
    of esoteric languages comprises of: (i) the hard-by-design primitives comprising the language; (ii) substantially less
    representation in pre-training corpora (340x to over 60,000x fewer public GitHub repositories than Python); (iii) negligible
    deployment value, which makes targeted inclusion in post-training data economically irrational. We evaluate five frontier
    models across five prompting strategies and find a dramatic capability gap. The same 80 problems expressed in Python or
    JavaScript reach 100% accuracy on top frontier models, while the equivalent esoteric versions score only 0-11%. Few-shot
    learning and self-reflection also fail to close this gap. EsoLang-Bench therefore provides a contamination-resistant testbed
    for measuring how well frontier models generalise algorithmic problem-solving to programming languages outside their training
    distribution.'
  publisher: arXiv.org.
  published_on: '2026-03-10'
  doi: null
links:
  source: http://arxiv.org/abs/2603.09678v2
  open_access: https://arxiv.org/abs/2603.09678v2
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

