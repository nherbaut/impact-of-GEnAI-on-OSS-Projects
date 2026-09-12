---
schema: paper-monitor/paper/v1
paper_id: 6852
record_type: PAPER
bibliography:
  title: '[PDF] ML-Bench: Evaluating Large Language Models and Agents for Machine Learning Tasks on Repository-Level Code'
  authors: Xiangru Tang, Yuliang Liu, Zefan Cai, Yanjun Shao, Junjie Lu, Yichi Zhang, Zexuan Deng, Helan Hu, Kaikai An, Ruijun
    Huang, Shuzheng Si, Sheng Chen, Haozhe Zhao, Liang Chen, Yan Wang, Tianyu Liu, Zhiwei Jiang, Baobao Chang, Yin Fang, Yujia
    Qin, Wangchunshu Zhou, Yilun Zhao, Arman Cohan, Mark Gerstein
  abstract: 'Despite Large Language Models (LLMs) like GPT-4 achieving impressive results in function-level code generation,
    they struggle with repository-scale code understanding (e.g., coming up with the right arguments for calling routines),
    requiring a deeper comprehension of complex file interactions. Also, recently, people have developed LLM agents that attempt
    to interact with repository code (e.g., compiling and evaluating its execution), prompting the need to evaluate their
    performance. These gaps have motivated our development of ML-Bench, a benchmark rooted in real-world programming applications
    that leverage existing code repositories to perform tasks. Addressing the need for LLMs to interpret long code contexts
    and translate instructions into precise, executable scripts, ML-Bench encompasses annotated 9,641 examples across 18 GitHub
    repositories, challenging LLMs to accommodate user-specified arguments and documentation intricacies effectively. To evaluate
    both LLMs and AI agents, two setups are employed: ML-LLM-Bench for assessing LLMs'' text-to-code conversion within a predefined
    deployment environment, and ML-Agent-Bench for testing autonomous agents in an end-to-end task execution within a Linux
    sandbox environment. Our findings indicate that while GPT-4o leads with a Pass@5 rate surpassing 50%, there remains significant
    scope for improvement, highlighted by issues such as hallucinated outputs and difficulties with bash script generation.
    Notably, in the more demanding ML-Agent-Bench, GPT-4o achieves a 76.47% success rate, reflecting the efficacy of iterative
    action and feedback in complex task resolution. Our code, dataset, and models are available at https://github.com/gersteinlab/ML-bench.'
  publisher: arXiv.org.
  published_on: '2023-11-16'
  doi: null
links:
  source: http://arxiv.org/abs/2311.09835v5
  open_access: https://arxiv.org/abs/2311.09835v5
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

