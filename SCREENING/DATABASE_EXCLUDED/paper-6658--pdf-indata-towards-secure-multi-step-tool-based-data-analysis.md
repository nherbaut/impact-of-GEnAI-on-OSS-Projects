---
schema: paper-monitor/paper/v1
paper_id: 6658
record_type: PAPER
bibliography:
  title: '[PDF] InData: Towards Secure Multi-Step, Tool-Based Data Analysis'
  authors: Karthikeyan K, Raghuveer Thirukovalluru, Bhuwan Dhingra, David Edwin Carlson
  abstract: 'Large language model agents for data analysis typically generate and execute code directly on databases. However,
    when applied to sensitive data, this approach poses significant security risks. To address this issue, we propose a security-motivated
    alternative: restrict LLMs from direct code generation and data access, and require them to interact with data exclusively
    through a predefined set of secure, verified tools. Although recent tool-use benchmarks exist, they primarily target tool
    selection and simple execution rather than the compositional, multi-step reasoning needed for complex data analysis. To
    reduce this gap, we introduce Indirect Data Engagement (InData), a dataset designed to assess LLMs'' multi-step tool-based
    reasoning ability. InData includes data analysis questions at three difficulty levels--Easy, Medium, and Hard--capturing
    increasing reasoning complexity. We benchmark 15 open-source LLMs on InData and find that while large models (e.g., gpt-oss-120b)
    achieve high accuracy on Easy tasks (97.3%), performance drops sharply on Hard tasks (69.6%). These results show that
    current LLMs still lack robust multi-step tool-based reasoning ability. With InData, we take a step toward enabling the
    development and evaluation of LLMs with stronger multi-step tool-use capabilities. We will publicly release the dataset
    and code.'
  publisher: arXiv.org.
  published_on: '2025-11-14'
  doi: null
links:
  source: http://arxiv.org/abs/2511.11933v1
  open_access: https://arxiv.org/abs/2511.11933v1
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

