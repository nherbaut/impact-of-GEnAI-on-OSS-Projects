---
schema: paper-monitor/paper/v1
paper_id: 6577
record_type: PAPER
bibliography:
  title: '[PDF] Research and prototyping study of an LLM-based chatbot for electromagnetic simulations'
  authors: Albert Piwonski, Mirsad Hadžiefendić
  abstract: Purpose This study aims to address the question of how generative artificial intelligence can be used to reduce
    the time required to set up electromagnetic simulation models. A chatbot based on a large language model (LLM) is presented,
    enabling the automated generation of simulation models with various functional enhancements. Design/methodology/approach
    A chatbot-driven workflow based on the LLM Google Gemini-2.0-Flash automatically generates and solves two-dimensional
    finite element eddy current models using Gmsh and GetDP. Python is used to coordinate and automate interactions between
    the workflow components. The study considers conductor geometries with circular cross-sections of variable position and
    number. In addition, users can define custom postprocessing routines and receive a concise summary of model information
    and simulation results. Each functional enhancement includes the corresponding architectural modifications and illustrative
    case studies. Findings With a defined set of functionalities, the chatbot successfully sets up and solves electromagnetic
    simulation models. Notably, it automatically infers not only Python code but also the domain-specific language code for
    GetDP. The case studies conducted revealed open research challenges, particularly with regard to the question of how to
    ensure that results are both syntactically and semantically valid. Originality/value Currently, the application of machine
    learning methods to solve electromagnetic boundary value problems is an active area of research (see, e.g. physics-informed
    neural networks or neural operators). However, to the best of the authors’ knowledge, little research has examined the
    potential of artificial-intelligence-assisted generation of simulation models that prioritizes code generation and execution
    rather than the enhancement of numerical solution schemes. This study leverages a LLM and designs tailored workflows that
    contextualize it through carefully constructed system prompts.
  publisher: COMPEL the International Journal for Computation and Mathematics in Electrical and Electronic Engineering.
  published_on: '2026-05-15'
  doi: 10.1108/compel-10-2025-0505
links:
  source: https://doi.org/10.1108/compel-10-2025-0505
  open_access: https://doi.org/10.1108/compel-10-2025-0505
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

