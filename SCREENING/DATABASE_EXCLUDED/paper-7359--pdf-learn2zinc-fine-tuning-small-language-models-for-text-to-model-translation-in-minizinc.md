---
schema: paper-monitor/paper/v1
paper_id: 7359
record_type: PAPER
bibliography:
  title: '[PDF] Learn2Zinc: Fine-tuning Small Language Models for Text-to-Model Translation in MiniZinc'
  authors: Serdar Kadioglu, Karthik Uppuluri
  abstract: 'Large language models excel at code generation for mainstream programming languages but struggle with rare, domain-specific
    languages such as MiniZinc, a constraint modeling language for combinatorial problems. We investigate whether targeted
    fine-tuning can teach small language models (0.6B to 20B parameters) to generate syntactically correct and semantically
    valid MiniZinc models from natural language problem descriptions. Our key finding is that syntax errors dominate failures
    when working with this domain specific language: the out-of-the-box execution accuracy of small language models such as
    Qwen3, LLaMa, Gemma, and GPT-OSS is near-zero. We propose a cross-model error bootstrapping approach that collects syntax
    errors from multiple LLM runs and leverage those to curate an error correction training dataset. This dataset allows us
    fine-tune small language models that consistently improves both direct code generation and chain-of-thought approaches
    across all model sizes. With self-reflection and ensembling, our approach achieves up to 98\% execution accuracy. In parallel,
    solution accuracy still remains at 35\%, indicating that while syntax is learnable, constraint reasoning remains a challenge.
    We contribute our fine-tuning pipeline, datasets, and models to opens-source for further research on text-to-model translation.'
  publisher: arXiv.org.
  published_on: '2026-05-14'
  doi: null
links:
  source: http://arxiv.org/abs/2607.20456v1
  open_access: https://arxiv.org/abs/2607.20456v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-07-24T07:41:32.829200Z'
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

