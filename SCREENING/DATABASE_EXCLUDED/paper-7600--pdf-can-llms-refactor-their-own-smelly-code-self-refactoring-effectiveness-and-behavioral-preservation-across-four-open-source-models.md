---
schema: paper-monitor/paper/v1
paper_id: 7600
record_type: PAPER
bibliography:
  title: '[PDF] Can LLMs Refactor Their Own Smelly Code? Self-Refactoring Effectiveness and Behavioral Preservation Across
    Four Open-Source Models'
  authors: Dong Kwan Kim, Young-Wuk Lee, Jung-Sik Jeong
  abstract: '(1) Background: LLM-generated code frequently contains code smells that degrade maintainability. Whether the
    generating model can effectively refactor its own output—self-refactoring—remains untested. (2) Methods: We construct
    a taxonomy of six LLM-specific Python 3.12 code smells (F1 = 0.87) and test self-refactoring across 1404 real-inference
    smelly snippets from four open-source LLMs (CodeLlama-13B, DeepSeekCoder-6.7B, StarCoder2-15B, Qwen2.5-Coder-14B) on BigCodeBench.
    (3) Results: Three self-refactoring profiles emerge: style entrenchment (CodeLlama, 0% median SRR), inherent capability
    (DeepSeekCoder, 100%), and prompt-dependent (Qwen, 100% with smell-aware prompting vs. 0% zero-shot). Because one smell
    (Narrative Comment) dominates, per-smell-type results are foregrounded and StarCoder2 (n=14) is preliminary. Unit tests
    confirm a 96.0% Behavioral Preservation Rate on test-passing snippets (95% CI 93.3–97.7%). A direct cross-refactoring
    experiment (356 runs, four independent refactorers) falsifies the Style Coherence Hypothesis: self-refactoring never beats
    the best independent model (0/89 snippets), and CodeLlama’s own code—which it cleans in 1/25 cases—is cleaned in 25/25
    by other models (p=4.8×10−7). A generation–refactoring feedback loop, strong in simulation, is likewise null under real
    inference. (4) Conclusions: Self-refactoring effectiveness depends on the interaction of model, smell type, and prompting
    strategy. Smell-aware prompting enables lightweight, behavior-preserving post-generation quality pipelines without extra
    models or retraining; the closed-loop feedback variant, by contrast, does not transfer from simulation to real inference.'
  publisher: Applied Sciences Switzerland.
  published_on: '2026-08-04'
  doi: 10.3390/app16157733
links:
  source: https://doi.org/10.3390/app16157733
  open_access: https://doi.org/10.3390/app16157733
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-08-19T14:01:02.452399Z'
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

