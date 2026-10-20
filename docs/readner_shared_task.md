---
layout: default
title: READNER 2027 shared task
nav_order: 6
---

# READNER 2027: Named Entity Recognition in GitHub READMEs

READNER 2027 is a fine-grained Named Entity Recognition (NER) shared task at the Workshop on AI for the Scholarly Web (NSLP-SDP 2027). It addresses research-related GitHub README files, where metadata about datasets, software, experimental code, and other research artifacts is often embedded in free-form documentation.

NFDI4DataScience (NFDI4DS) supports the research data lifecycle in Data Science and Artificial Intelligence, from collecting and processing resources to publishing, archiving, and reusing them. GitHub repositories complement research papers by providing datasets, models, source code, and implementation details that help researchers explore and reproduce results. Their README files typically describe the project's purpose, setup, and usage, and link to related research resources. READNER extracts structured metadata from README documents for research resource discovery and reuse.

## Task definition

Participants develop systems that take a GitHub README file as input and identify entity mentions, their boundaries, and their types. The task covers the following ten entity types from the NFDI4DS Ontology (NFDI4DSO) [1]:

1. Conference
2. Dataset
3. Evaluation Metric
4. License
5. Ontology
6. Programming Language
7. Project
8. Publication
9. Software
10. Workshop

## Dataset

The shared task uses NERdME [2], a dataset of **200 manually annotated GitHub READMEs** containing **10,691 entity mentions** across **ten entity types**. By covering both paper-level and implementation-level research entities, the dataset connects scientific information extraction with software-repository documentation.

## Evaluation and submissions

Partial- and Exact-boundary recognition is a particular challenge for existing LLM and transformer baselines on this dataset [2], leaving room for improved identification of entity mentions and their boundaries.

Each prediction identifies an entity mention, its span boundaries, and one of the ten entity types listed above.

## Competition platform

READNER 2027 uses [CodaBench](https://www.codabench.org/competitions/18427/) for system submissions. The competition launches on December 1, 2026.

## Important dates

| Milestone | Date |
| --- | --- |
| Datasets released | December 1, 2026 |
| CodaBench instance publication | December 1, 2026 |
| System submission deadline on CodaBench | January 4, 2027 |
| Paper submission deadline | January 11, 2027 |
| Notification of acceptance | February 8, 2027 |
| Camera-ready deadline | February 16, 2027 |

## Organizers

* Genet Asefa Gesese (FIZ Karlsruhe, Germany)
* Zongxiong Chen (Fraunhofer FOKUS, Germany)
* Mary Ann Tan (FIZ Karlsruhe, Germany)
* Sonja Schimmler (Fraunhofer FOKUS, Germany)

## Contact

* Genet Asefa Gesese (FIZ Karlsruhe, Germany): [genet-asefa.gesese@fiz-karlsruhe.de](mailto:genet-asefa.gesese@fiz-karlsruhe.de)
* Zongxiong Chen (Fraunhofer FOKUS, Germany): [zongxiong.chen@fokus.fraunhofer.de](mailto:zongxiong.chen@fokus.fraunhofer.de)
* Mary Ann Tan (FIZ Karlsruhe, Germany): [ann.tan@fiz-karlsruhe.de](mailto:ann.tan@fiz-karlsruhe.de)

## References

[1] Genet Asefa Gesese et al. [NFDI4DSO: Towards a BFO Compliant Ontology for Data Science](https://arxiv.org/abs/2408.08698). arXiv:2408.08698 (2024).

[2] Genet Asefa Gesese et al. [Named entity recognition dataset for research artifacts in code repositories](https://doi.org/10.1145/3774904.3792934). In Proceedings of the ACM Web Conference 2026, pp. 8661-8664 (2026).
