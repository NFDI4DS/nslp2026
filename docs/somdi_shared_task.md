---
layout: default
title: SOMDi shared task
nav_order: 6
---

# SOMDi2026: Software Mention Disambiguation

Understanding software mentions is crucial for reproducibility and to interpret experimental results. Citations of software are often informal, lacking the use of persistent identifiers, making it hard to infer and disambiguate knowledge about software efficiently. This task will build on [SOMD 2025](https://sdproc.org/2025/sharedtasks.html#somd) (run at [SDP 2025](https://sdproc.org/2025/), co-located with ACL 2025) and focus on entity disambiguation as an under-investigated problem in this context. More precisely, SOMDi2026 will tackle the following tasks:

**Subtask 1:** Coreference resolution over gold standard mentions across multiple documents. 
Given all gold-standard annotated software mentions (including metadata and their sentences), the objective of this task is to generate clusters in which each cluster represents mentions referring to the same underlying software.

**Subtask 2:** Coreference resolution over predicted mentions across multiple documents. 
In this subtask, we provide annotated software mentions and their metadata, which are automatically extracted using a baseline model. The challenge is to resolve all co-references to the same software by creating clusters of mentions referring to the same software. This reflects real-world co-reference resolution, where upstream pipelines (such as entity and metadata extraction) are imperfect. 


**Subtask 3:** Coreference resolution over predicted mentions across multiple documents at scale
For this subtask, we provide predicted mentions of software and metadata at a larger scale.  Participants are expected to resolve coreferences to the same software by creating clusters of mentions referring to the same software. Since there are many more entity variants and numerous possible software identities in the provided corpus, this increases the computational runtime challenge for the coreference resolution task. This challenges models to scale effectively, maintain accuracy, and distinguish among an increasingly dense field of similar or overlapping software mentions.

