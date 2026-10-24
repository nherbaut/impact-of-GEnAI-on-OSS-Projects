---
schema: paper-monitor/paper/v1
paper_id: 6594
record_type: PAPER
bibliography:
  title: 'Prompt, Assert, Repeat: Test-Driven Prompting as a Quality Assurance Strategy for Code-Generating LLMs'
  authors: Brahma Reddy Korraprolu, Mohan Gangadhar Gudey, Y Diwakar Reddy, Dhiraj SM Varanasi
  abstract: Code-generating LLMs are increasingly used in software development, but compiling code does not imply functional
    correctness; outputs must be tested. This paper studies a lightweight QA strategy where unit tests are embedded in the
    prompt to guide code generation, followed by execution against a fixed test suite. Using the Mostly Basic Python Problems
    (MBPP) benchmark (964 problems, 3 assertions each), we evaluate twelve open-source LLMs with (i) plain prompts and (ii)
    assertionaugmented prompts, generating five samples per configuration and measuring pass@1 and pass@5. We find that including
    assertions often yields large correctness gains (frequently 20-30 points in pass@5), but the effect is model and problem-type
    dependent, with notable degradations for some instruction-tuned models. Across problem types, conditional-logic tasks
    are consistently easier, while recursion-heavy categories (e.g., dynamic programming/tree traversal) remain challenging.
    Based on these results, we outline SQA guidance on when test-driven prompting and limited resampling are effective for
    improving correctness in LLM-assisted programming.
  publisher: Proceedings 2026 IEEE International Conference on Software Analysis Evolution and Reengineering Companion Saner
    C 2026
  published_on: '2026-03-17'
  doi: 10.1109/saner-c67878.2026.00049
links:
  source: https://doi.org/10.1109/saner-c67878.2026.00049
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

