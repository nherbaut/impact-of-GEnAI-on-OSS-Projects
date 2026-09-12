---
schema: paper-monitor/paper/v1
paper_id: 6625
record_type: PAPER
bibliography:
  title: '[PDF] MapCoder-Lite: Distilling Multi-Agent Coding into a Single Small LLM'
  authors: Woongkyu Lee, Junhee Cho, Jungwook Choi
  abstract: 'Large language models (LLMs) have advanced code generation from single-function tasks to competitive-programming
    problems, but existing multi-agent solutions either rely on costly large-scale (> 30B) models or collapse when downsized
    to small open-source models.We present MapCoder-Lite, a framework for distilling the complex reasoning of large, multi-agent
    coding systems into a single 7B model.Our contribution is a novel, three-pillar methodology that synergistically generates,
    refines, and encodes multi-agent knowledge: (i) pass-based trajectory distillation from strong LLMs fixes format fragility
    in retrieval and reduces failures in debugging, (ii) supervisor-guided correction with global feedback strengthens planning
    and coding agents, and (iii) agent-wise LoRA fine-tuning delivers memory-efficient specialisation.Comprehensive evaluation
    on xCodeEval, APPS, and CodeContests shows that MapCoder-Lite more than doubles xCodeEval accuracy (13.2% 28.3%), eliminates
    all format failures, while reducing GPU memory and token-generation time by 4 compared to a 32B model.It also achieves
    over 10% gains on simpler coding benchmarks, demonstrating broad improvements beyond competitive programming.These results
    demonstrate that careful agent-wise fine-tuning unleashes highquality multi-agent coding on a small language model.Our
    code is publicly available at https: //github.com/aiha-lab/MapCoder-Lite.'
  publisher: 19th Conference of the European Chapter of the Association for Computational Linguistics Findings of Eacl 2026.
  published_on: '2026-01-01'
  doi: 10.18653/v1/2026.findings-eacl.346
links:
  source: https://doi.org/10.18653/v1/2026.findings-eacl.346
  open_access: https://aclanthology.org/2026.findings-eacl.346.pdf
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

