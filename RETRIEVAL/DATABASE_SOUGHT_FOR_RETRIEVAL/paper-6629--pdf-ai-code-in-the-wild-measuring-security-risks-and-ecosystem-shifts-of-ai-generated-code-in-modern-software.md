---
schema: paper-monitor/paper/v1
paper_id: 6629
record_type: PAPER
bibliography:
  title: '[PDF] AI Code in the Wild: Measuring Security Risks and Ecosystem Shifts of AI-Generated Code in Modern Software'
  authors: Bin Wang, Wenjie Yu, Yilu Zhong, Hao Yu, Keke Lian, Chaohua Lu, Hongfang Zheng, Dong Zhang, Hui Li
  abstract: 'Large language models (LLMs) for code generation are becoming integral to modern software development, but their
    real-world prevalence and security impact remain poorly understood. We present the first large-scale empirical study of
    AI-generated code (AIGCode) in the wild. We build a high-precision detection pipeline and a representative benchmark to
    distinguish AIGCode from human-written code, and apply them to (i) development commits from the top 1,000 GitHub repositories
    (2022-2025) and (ii) 7,000+ recent CVE-linked code changes. This lets us label commits, files, and functions along a human/AI
    axis and trace how AIGCode moves through projects and vulnerability life cycles. Our measurements show three ecological
    patterns. First, AIGCode is already a substantial fraction of new code, but adoption is structured: AI concentrates in
    glue code, tests, refactoring, documentation, and other boilerplate, while core logic and security-critical configurations
    remain mostly human-written. Second, adoption has security consequences: some CWE families are overrepresented in AI-tagged
    code, and near-identical insecure templates recur across unrelated projects, suggesting "AI-induced vulnerabilities" propagated
    by shared models rather than shared maintainers. Third, in human-AI edit chains, AI introduces high-throughput changes
    while humans act as security gatekeepers; when review is shallow, AI-introduced defects persist longer, remain exposed
    on network-accessible surfaces, and spread to more files and repositories. We will open-source the complete dataset and
    release analysis artifacts and fine-grained documentation of our methodology and findings.'
  publisher: arXiv.org.
  published_on: '2025-12-21'
  doi: null
links:
  source: http://arxiv.org/abs/2512.18567v1
  open_access: https://arxiv.org/abs/2512.18567v1
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-06-30T13:29:23.865282Z'
workflow:
  state:
    id: RETRIEVAL/DATABASE_SOUGHT_FOR_RETRIEVAL
    label: Database sought for retrieval
    prisma_bucket: DATABASE_SOUGHT_FOR_RETRIEVAL
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

