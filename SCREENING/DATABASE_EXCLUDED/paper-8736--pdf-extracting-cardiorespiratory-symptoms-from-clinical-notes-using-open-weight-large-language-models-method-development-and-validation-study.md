---
schema: paper-monitor/paper/v1
paper_id: 8736
record_type: PAPER
bibliography:
  title: '[PDF] Extracting Cardiorespiratory Symptoms From Clinical Notes Using Open-Weight Large Language Models: Method
    Development and Validation Study'
  authors: Yunbing Bai, Wanting Cui, Joseph Finkelstein
  abstract: 'Background: Accurate identification of clinical symptoms and signs (S&S) is essential for the early detection
    of high-burden cardiorespiratory conditions, including lung cancer, chronic obstructive pulmonary disease, and heart failure.
    Although symptom data play a central role in diagnostic reasoning and predictive modeling, most S&S information remains
    embedded in unstructured electronic health record notes, limiting their use in automated phenotyping, surveillance, and
    clinical decision support. Traditional natural language processing systems struggle with domain variability and contextual
    nuance in clinical text. Recent advances in large language models (LLMs) offer a promising alternative, yet challenges
    remain in hallucinations, overinference, and safe deployment. This study evaluated whether locally deployed open-source
    models could reliably extract cardiorespiratory S&S and map them to ICD-10-CM (International Classification of Diseases,
    Tenth Revision, Clinical Modification) codes using optimized prompting strategies. Objective: This study aims to assess
    the accuracy of open-source LLMs in extracting explicitly stated cardiorespiratory S&S from clinical notes and mapping
    them to ICD-10-CM codes (R00-R09) and to compare performance across 4 prompt-engineering strategies, including a multimodule
    LLM framework. Methods: A total of 593 clinical notes from the MTSamples database were manually reviewed, with 93 notes
    used for prompt development and comparison using Llama 3.3-70B, and 500 notes used as testing data for the final best
    prompt setting using both Llama 3.3-70B and gpt-oss-120B. Four prompting conditions were evaluated: (1) instruction-only,
    (2) ICD-10-CM definition-based prompts, (3) assumption-free prompts, and (4) a multimodule LLM framework with postprocessing.
    Performance was measured using precision, recall, and F1-score for both S&S extraction and ICD-10-CM code generation.
    Results: Across all prompt strategies, model performance improved as more structure and constraints were added. Instruction-only
    prompting demonstrated high recall but poor precision. Incorporating ICD-10-CM definitions improved coding accuracy, and
    assumption-free prompting further balanced precision and recall. The multimodule approach with postprocessing achieved
    the highest performance during prompt development. On the independent test corpus, entity-level microaveraged evaluation
    showed that gpt-oss-120B outperformed Llama 3.3-70B in both tasks. For S&S extraction, Llama 3.3-70B achieved a precision
    of 0.63, a recall of 0.86, and an F1-score of 0.73, whereas gpt-oss-120B achieved a precision of 0.89, a recall of 0.87,
    and an F1-score of 0.88. For ICD-10-CM code mapping, Llama 3.3-70B achieved a precision of 0.59, a recall of 0.83, and
    an F1-score of 0.69, whereas gpt-oss-120B achieved a precision of 0.90, a recall of 0.84, and an F1-score of 0.87. Conclusions:
    Locally deployed LLMs, when paired with optimized prompting and multimodule orchestration, can accurately extract cardiorespiratory
    S&S and generate ICD-10-CM codes from unstructured clinical notes. This approach increases the level of data safety by
    enabling on-premises processing without external data transmission and demonstrates strong potential for scalable, domain-adaptive
    symptom extraction pipelines in biomedical informatics. Future work should expand datasets and evaluate generalizability
    across clinical domains.'
  publisher: Jmir Cardio.
  published_on: '2026-05-22'
  doi: 10.2196/89480
links:
  source: https://doi.org/10.2196/89480
  open_access: https://cardio.jmir.org/2026/1/e89480/PDF
source:
  logical_feed_id: 29
  logical_feed_name: impact of GEnAI on OSS Projects
  feed_id: 37
  feed_name: Miage Scholar Import 2026-06-30:15:30:01 RSS
  discovered_at: '2026-09-06T10:24:51.308436Z'
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

