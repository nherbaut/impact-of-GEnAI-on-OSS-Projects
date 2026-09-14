---
schema: paper-monitor/paper/v1
paper_id: 7626
record_type: PAPER
bibliography:
  title: '[PDF] SetGo: Metadata Readiness for Scientific AI Datasets'
  authors: Sean R. Wilkinson, Polina Shpilker, Wesley Brewer
  abstract: 'Scientific datasets intended for AI use require both computational readiness for model training and metadata
    readiness for discovery, sharing, and reuse. The Readiness Engine for Data Integration (REDI) addresses computational
    readiness, but no corresponding tool evaluates whether a dataset''s metadata are sufficiently complete, governed, and
    standards-compliant for publication and agent-based consumption. Existing FAIR assessors operate only on published repository
    records, and no single system covers FAIR compliance, licensing, provenance, governance, reproducibility, and catalog
    readiness together. We present SetGo, an open-source Python toolkit that assesses and repairs metadata readiness across
    these six dimensions before a dataset is published or archived. Applied to four scientific corpora, SetGo surfaces deficiencies
    that general-purpose tools do not detect: ERA5 climate metadata scores 4% on ACDD 1.3 compliance; materials datasets fail
    OPTIMADE species-definition requirements; and PDB-derived proteomics data carries licensing terms incompatible with standard
    SPDX identifiers. Guided enrichment raises overall FAIR scores from 52-57% to 81-91%, and a single setgo publish command
    pushes to Hugging Face Hub, CKAN, or OpenMetadata with ML Commons Croissant 1.0 metadata sidecars. To support interactive
    and automated workflows, SetGo integrates with coding agents powered by large language models (LLMs) through a /setgo
    skill that enables natural-language execution of the full assess-enrich-publish loop, with user involvement limited to
    supplying missing metadata values.'
  publisher: Ssdbm 2026 38th International Conference on Scalable Scientific Data Management.
  published_on: '2026-07-10'
  doi: 10.1145/3828820.3828827
links:
  source: https://doi.org/10.1145/3828820.3828827
  open_access: https://arxiv.org/pdf/2607.22677
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-08-22T15:02:48.440512Z'
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

