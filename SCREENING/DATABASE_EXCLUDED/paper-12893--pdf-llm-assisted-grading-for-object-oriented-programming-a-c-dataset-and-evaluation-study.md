---
schema: paper-monitor/paper/v1
paper_id: 12893
record_type: PAPER
bibliography:
  title: '[PDF] LLM-Assisted Grading for Object-Oriented Programming: A C++ Dataset and Evaluation Study'
  authors: Adrian-Gabriel Diaconu, Alexandru Guzu, A. Ulmamei
  abstract: 'Large language models (LLMs) are increasingly used in programming tasks, including code generation, debugging,
    validation, optimization, test generation, and educational support. Their use as graders of student programming assignments
    is, however, still not fully understood, especially in object-oriented programming (OOP). In this context, correctness
    depends not only on the final output of a program but also on class structure, encapsulation, abstraction, and design
    decisions. This paper introduces a dataset of 271 C++ student solutions to eight OOP examination problems, together with
    the problem statements and the reference grades produced by the university auto-grader. We evaluate four locally served
    open-weight models—phi4-mini, gpt-oss:20b, qwen3.6:27b, and qwq:32b—under one endpoint, one prompt, and deterministic
    decoding, and we report four properties that a deployable grader must have. The first is output-format compliance, which
    ranges from 88.9% to 98.9% across models: qwq:32b failed to terminate on 30 of 271 submissions even at a doubled generation
    budget, spending 7.7 MJ, 29.9% of its total energy, to produce nothing. The second is agreement with the reference grades
    on the 30-point course scale, where qwen3.6:27b performs best (MAE 3.23 points, r=0.85) and phi4-mini worst (MAE 10.90,
    r=0.17); all four models grade systematically more strictly than the auto-grader. The third is reproducibility, which
    fails at two levels. Repeating an identical run, three models returned identical grades at temperature 0 with a fixed
    seed while gpt-oss:20b varied by up to 21 points on the same submission; restricting the serving daemon to one concurrent
    request makes it reproducible, locating that failure in request batching rather than in sampling. Grading the same submissions
    as part of a different set, however, no model is reproducible: agreement with the original run ranges from 13 to 33 of
    40 submissions, and a control run with the original client excludes our instrumentation as the cause. The fourth is degeneracy:
    phi4-mini awarded an identical grade of zero to every submission in three of the eight examinations, 109 submissions in
    total, so its aggregate agreement statistics describe a model that is not grading. On a subset graded blind by two instructors,
    each instructor agreed with the auto-grader more closely than the two agreed with each other, so the residual error of
    the best-performing model is of the same order as ordinary disagreement between human graders. We also report a negative
    result: a declaration-level reference could be reconstructed for only five of the eight examinations, because the auto-grader
    merges missing declarations and wrong return values into single checks. Together these results indicate that agreement
    with a reference is an insufficient basis for choosing a local grading model, and that compliance, determinism, degeneracy,
    and the cost of failed generations must be measured alongside it.'
  publisher: Electronics Switzerland.
  published_on: '2026-09-21'
  doi: 10.3390/electronics15184331
links:
  source: https://doi.org/10.3390/electronics15184331
  open_access: https://doi.org/10.3390/electronics15184331
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-10-04T12:14:22.898402Z'
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

