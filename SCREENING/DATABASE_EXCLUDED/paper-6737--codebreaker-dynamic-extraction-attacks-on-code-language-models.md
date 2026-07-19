---
schema: paper-monitor/paper/v1
paper_id: 6737
record_type: PAPER
bibliography:
  title: 'Codebreaker: Dynamic Extraction Attacks on Code Language Models'
  authors: Changzhou Han, Zehang Deng, Wanlun Ma, Xiaogang Zhu, Minhui Xue, Tianqing Zhu, Sheng Wen, Yang Xiang
  abstract: 'With the rapid adoption of LLM-based code assistants to enhance programming experiences, concerns over extraction
    attacks targeting private training data have intensified. These attacks specifically aim to extract Personal Information
    (PI) embedded within the training data of code generation models (CodeLLMs). Existing methods, using either manual or
    semi-automated techniques, have successfully extracted sensitive data from these CodeLLMs. However, the limited amount
    of data currently retrieved by extraction attacks risks significantly underestimating the true extent of training data
    leakage. In this paper, we propose an automatic PI data extraction attack framework against LLM-based code assistants,
    named Codebreaker. This framework is built on two core components: (i) the introduction of semantic entropy, which evaluates
    the likelihood of a prompt triggering the model to respond with training data; and (ii) an automatic dynamic mutation
    mechanism that seamlessly integrates with Codebreaker, reinforcing the iterative process across the framework and promoting
    greater interconnection between different PI elements within a single response. This boosts reasoning diversity, model
    memorization, and finally attack performance. Using six series of open-source CodeLLMs (i.e., CodeParrot, StarCoder2,
    Code Llama, CodeGemma, DeepSeek-Coder, DeepSeek-V3) and two commercial code assistants (i.e., CodeFuse and GPT), we demonstrate
    the effectiveness of our proposed framework: (i) Codebreaker outperforms all current state-of-the-art extraction attacks
    by 6.22% ~ 44.9% (averaging 21.79%); (ii) when PI within a single response originates from the same GitHub repository,
    our framework - considering multiple interconnections in the response - exceeds others by 3.88% ~ 32.37% (averaging 15.31%).
    Furthermore, we discuss potential defenses, highlighting the urgent need for stronger measures to prevent PI leakage at
    the base model level.'
  publisher: Proceedings IEEE Symposium on Security and Privacy
  published_on: '2025-05-12'
  doi: 10.1109/sp61157.2025.00124
links:
  source: https://doi.org/10.1109/sp61157.2025.00124
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

