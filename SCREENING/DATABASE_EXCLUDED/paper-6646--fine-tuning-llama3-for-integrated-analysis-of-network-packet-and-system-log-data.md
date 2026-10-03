---
schema: paper-monitor/paper/v1
paper_id: 6646
record_type: PAPER
bibliography:
  title: Fine-tuning Llama3 for Integrated Analysis of Network Packet and System Log Data
  authors: Hyun‐Min Choi, Youngseok Lee
  abstract: As cyber threats grow more complex, the need for intelligent and unified analysis across diverse security data
    sources becomes increasingly critical. To meet this demand, we present Llama-PcapLog, a fine-tuned LLM framework that
    jointly interprets network packets (pcap) and system logs (syslog), which automates threat detection and scenario analysis.
    Unlike prior methods that treat pcap and syslog analysis modalities in isolation, Llama-PcapLog captures their temporal
    and contextual dependencies to detect complex attack patterns. To bridge structural gaps and preserve cross-layer semantics,
    we fine-tune the open-source LLM by considering pcap and syslog data. For fine-tuning open-source LLM, we preprocess raw
    pcap and syslog data into an instruction-following format. We also employ a self-instruct strategy to generate diverse,
    domain-specific tasks across Q&A and code generation. As many institutions or companies need on-premise or private LLM
    to protect their customers’ privacy and data, we fine-tune the Meta Llama-3-8B model on the training dataset and developed
    a lightweight web interface for interactive analysis. We show that Llama-PcapLog achieves substantial improvements over
    the base Llama-3-8B with an overall extraction F1 score increase from 0.27 to 0.75. Experiments also show that Llama-PcapLog
    attains a perfect Pass@k score of 1.00 (vs. 0.45) in the code generation benchmark. These results highlight its effectiveness
    and potential deployability in real-world cybersecurity workflows.
  publisher: 2025 30th Asia Pacific Conference on Communications Apcc 2025
  published_on: '2025-11-26'
  doi: 10.23919/apcc64555.2025.11279921
links:
  source: https://doi.org/10.23919/apcc64555.2025.11279921
  open_access: null
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

