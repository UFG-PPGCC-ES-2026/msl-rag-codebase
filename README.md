# msl-rag-codebase

> **Retrieval-Augmented Generation Applied to Software Codebases: A Systematic Mapping Study**

This repository contains all artifacts produced during the conception and development of a systematic mapping study on Retrieval-Augmented Generation (RAG) applied to software codebases. The final output of this research is a scientific article submitted as a requirement for the **Graduate Program in Computer Science (PPGCC)** at the **Universidade Federal de Goiás (UFG)**.

## Authors

| Name | E-mail | Program |
|------|---------|---------|
| Alex Ferreira de Almeida | almeida_alex@discente.ufg.br | PPGCC-UFG |
| Paulo Augusto de Oliveira Gonçalves | goncalves2@discente.ufg.br | PPGCC-UFG |

**Advisor:** Prof. Dr. Valdemar Vicente Graciano Neto

## Research Overview

**Objective (GQM):** To analyze RAG approaches based on Large Language Models (LLMs) applied to software codebases, with the purpose of identifying and classifying their techniques, employed LLMs, studied languages and systems, evaluation metrics, and existing gaps — from the perspective of Software Engineering researchers and practitioners — in the context of primary studies published between 2020 and 2026.

**Method:** Systematic Mapping Study (SMS), following the guidelines of Kitchenham & Charters (2007) and Petersen et al. (2015).

**Search String:**
```
("Retrieval-Augmented Generation" OR "RAG") AND
("source code" OR "codebase" OR "code repository") AND
("LLM" OR "Large Language Model" OR "GenAI" OR "Generative AI")
```

**Research Questions:**

- **RQ1:** What RAG techniques and architectures are proposed for application in software codebases?
- **RQ2:** Which Large Language Models are employed as the generator component in RAG approaches for codebases?
- **RQ3:** What programming languages and types of systems are most studied?
- **RQ4:** What metrics are used to evaluate the effectiveness of RAG approaches in codebases?
- **RQ5:** What are the main gaps identified in the literature on RAG applied to codebases?

**Search Sources:** IEEE Xplore, Scopus, ACM Digital Library

## Repository Structure

```
.
├── article/                  # Scientific article artifacts
│   ├── drafts/               # Working draft and revision history
│   │   ├── draft.docx        # Current working draft
│   │   ├── CHANGELOG.md      # Draft revision log
│   │   └── reviews/          # Annotated versions received from reviewers
│   ├── figures/              # Figures used in the article
│   ├── tables/               # Tables used in the article
│   └── final/                # Final submitted version(s)
│
├── research_protocol/        # Research protocol and methodological references
│   ├── protocol.docx         # Research protocol (versioned via Git)
│   ├── protocol.pdf          # PDF export of the current protocol version
│   ├── CHANGELOG.md          # Protocol decision log
│   └── references/
│       ├── guidelines/       # Methodological guidelines (Kitchenham, Petersen)
│       └── examples/         # Example studies used as reference
│
└── sources/                  # Data collected from search sources
    ├── search_strings.md     # Documented search strings per source
    ├── ieee/                 # IEEE Xplore results
    │   ├── raw/              # Raw exports (.bib, .csv) and search screenshots
    │   └── screened/         # Articles after title/abstract screening
    ├── scopus/               # Scopus results
    │   ├── raw/
    │   └── screened/
    └── acm/                  # ACM Digital Library results
        ├── raw/
        └── screened/
```

## License

This repository is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).