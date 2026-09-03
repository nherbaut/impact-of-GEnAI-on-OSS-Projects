---
schema: paper-monitor/paper/v1
paper_id: 6569
record_type: PAPER
bibliography:
  title: '[PDF] TeleSWEBench: A Commit-Driven Benchmark for Evaluating LLM-Powered Software Engineering in Telecommunications'
  authors: Pranshav Gajjar, Ali Mamaghani, Dinesh Bharadia, Vijay K Shah
  abstract: With the telecommunications field embracing zero touch management alongside novel O-RAN and AI-RAN frameworks,
    contemporary telecom networks now function as immensely intricate and heavily softwareized codebases. While automated
    software engineering (ASE) tools and Software Engineering (SWE) Agents hold the potential to alleviate the critical code
    generation bottleneck in this domain, their ability to navigate and modify specialized, mathematically rigorous wireless
    stacks like srsRAN 5G remains unverified. General-purpose coding benchmarks fail to capture the stateful logic and strict
    requirements of telecommunications, leaving a critical evaluation gap. In this paper, we introduce TeleSWEBench, the first
    commit-driven benchmark specifically designed to measure an agent's performance in the telecom domain. We mine real developer
    commits from the srsRAN 5G repository and distill them into structured test cases across three difficulty tiers (Easy,
    Medium, and Difficult). Our benchmark consists of 734 questions that are accompanied by executable unit tests. To avoid
    the rigidity of test cases, we further propose a hierarchical LLM as a Judge framework called TeleJudge that scores agent
    outputs at the file level and aggregates verdicts holistically. This follows an evaluation based on context and semantic
    similarity in parallel to a standard unit test-based evaluation. Using this benchmark, we evaluate AIDER, OpenHands, and
    the ClaudeCode frameworks, powered by state-of-the-art reasoning LLMs, including Qwen3, GPT OSS, Gemma 4, Kimi, and Qwencoder
    2.5. Our two-stage evaluation reveals that models suffer from a lack of both localization accuracy and functional correctness,
    with the strongest ASE tools achieving up to 25% of shippable changes.
  publisher: arXiv.org.
  published_on: '2026-06-03'
  doi: null
links:
  source: http://arxiv.org/abs/2606.05001v1
  open_access: https://arxiv.org/abs/2606.05001v1
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

