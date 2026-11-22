---
schema: paper-monitor/paper/v1
paper_id: 15539
record_type: PAPER
bibliography:
  title: '[PDF] AEG-Edit: Bridging API Evolution and Code Semantics for Accurate API Usage in Code Generation'
  authors: Yitong Lin, Haoye Tian, Dehai Zhao, Chao Ni, Xiaohu Yang, Xiaoxue Ren
  abstract: 'As APIs across standard libraries and software ecosystems evolve, the API knowledge frozen in pre-trained LLMs
    becomes outdated. Prompt-based methods supply updated documentation at inference time yet suffer from context neglect,
    often reverting to memorized deprecated usages. Existing parametric approaches, whether fine-tuning or model editing,
    face two common challenges: they treat API changes as textual fact updates, overlooking the changes in code semantics
    needed for executable correctness (C1), and lack a mechanism to concentrate updates on positions involved in the API evolution,
    causing parameter interference beyond the evolution boundary (C2). We propose AEG-Edit, which constructs a heterogeneous
    API evolution graph, encodes and aligns the graph signal with the LLM hidden space, and concentrates gradient effort on
    positions involved in the API evolution through API-weighted windowing and optimization. On RustEvo²+ (708 Rust tasks)
    and PyEvo (622 Python tasks) across two representative open-source LLMs at the 7–8B parameter scale, AEG-Edit achieves
    statistically significant Pass@1 gains on RustEvo²+, improving over the strongest baseline by up to 6.49% on Qwen2.5-7B-Instruct.
    Ablation and transferability analyses confirm that the heterogeneous API evolution graph drives the gains and transfers
    to alternative editing backbones.'
  publisher: Proceedings 2026 Proceedings of the 41st IEEE ACM International Conference on Automated Software Engineering
    Ase 2026.
  published_on: '2026-10-07'
  doi: 10.1145/3832783.3834415
links:
  source: https://doi.org/10.1145/3832783.3834415
  open_access: https://dl.acm.org/doi/pdf/10.1145/3832783.3834415?download=true
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-11-07T07:27:35.004833Z'
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

