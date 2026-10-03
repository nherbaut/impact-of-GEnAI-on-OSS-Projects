---
schema: paper-monitor/paper/v1
paper_id: 6579
record_type: PAPER
bibliography:
  title: '[PDF] From Natural Language to Verified Code: Toward AI Assisted Problem-to-Code Generation with Dafny-Based Formal
    Verification'
  authors: Md Erfan, Md Kamal Hossain Chowdhury, Ahmed Ryan, Md Rayhanur Rahman
  abstract: 'Large Language Models (LLMs) show promise in automated software engineering, yet their guarantee of correctness
    is frequently undermined by erroneous or hallucinated code. To enforce model honesty, formal verification requires LLMs
    to synthesize implementation logic alongside formal specifications that are subsequently proven correct by a mathematical
    verifier. However, the transition from informal natural language to precise formal specification remains an arduous task.
    Our work addresses this by providing the NaturalLanguage2VerifiedCode (NL2VC)-60 dataset: a collection of 60 complex algorithmic
    problems. We evaluate 11 randomly selected problem sets across seven open-weight LLMs using a tiered prompting strategy:
    contextless prompts, signature prompts providing structural anchors, and self-healing prompts utilizing iterative feedback
    from the Dafny verifier. To address vacuous verification, where models satisfy verifiers with trivial specifications,
    we integrate the uDebug platform to ensure functional validation. Our results show that while contextless prompting leads
    to near-universal failure, structural signatures and iterative self-healing facilitate a dramatic performance turnaround.
    Specifically, Gemma 4-31B achieved a 90.91\% verification success rate, while GPT-OSS 120B rose from zero to 81.82\% success
    with signature-guided feedback. These findings indicate that formal verification is now attainable for open-weight LLMs,
    which serve as effective apprentices for synthesizing complex annotations and facilitating high-assurance software development.'
  publisher: arXiv.org.
  published_on: '2026-04-24'
  doi: null
links:
  source: http://arxiv.org/abs/2604.22601v1
  open_access: https://arxiv.org/abs/2604.22601v1
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

