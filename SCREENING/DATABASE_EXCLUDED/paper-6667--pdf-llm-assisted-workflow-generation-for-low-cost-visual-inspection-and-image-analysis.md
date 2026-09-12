---
schema: paper-monitor/paper/v1
paper_id: 6667
record_type: PAPER
bibliography:
  title: '[PDF] LLM-assisted workflow generation for low-cost visual inspection and image analysis'
  authors: Antti Martikkala, Amirmohammad Daareyni, Antoine Queguineur, Iñigo Flores Ituarte
  abstract: 'This work presents a lightweight framework that uses large language models (LLMs) to co-generate user-interface
    schemas (JSON) and executable Python modules for custom image-analysis pipelines. Modules follow a simple, fixed interface,
    and the active configuration can be exported as a JSON. We evaluate module generation across three operator classes and
    four LLMs (48 generations): first-run success was 66.7% and eventual pass after repairs was 97.9%, with typical fixes
    limited to imports or signature mismatches. Feasibility is demonstrated on plywood-knot counting: with various illumination
    and zoom the exported pipeline processed most test images correctly, however with larger changes in lighting/scale parameter
    retuning might be necessary. The approach targets low-cost settings by relying on open-source libraries and on possible
    deployments on low-cost embedded platforms (e.g., Raspberry Pi or Jetson) is feasible subject to processing-throughput
    constraints. The framework reduces integration effort for users with basic Python skills and supports rapid iteration
    in domains such as materials microscopy and visual inspection.'
  publisher: Iet Conference Proceedings.
  published_on: '2025-11-01'
  doi: 10.1049/icp.2025.3637
links:
  source: https://doi.org/10.1049/icp.2025.3637
  open_access: https://digital-library.theiet.org/doi/pdf/10.1049/icp.2025.3637?download=true
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

