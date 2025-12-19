---
layout: default
title: SOMD shared task
nav_order: 6
---
<div align="center" style="margin: 0px auto;"> 
<img width="450" height="500" src="../somd_logo.png" alt="somd_logo" />
<br/>
  
<h1> SOMD 2026: Software Mention Detection and Coreference Resolution </h1>
</div>
We address the task of coreference resolution of software mentions across multiple documents, i.e. given a set of software mentions extracted from multiple scientific publications, related extracted attributes as well as sentences in which these occur, cluster these mentions so that all software mentions in a particular cluster refer to the same real world software. 
This task will build on [SOMD 2025](https://sdproc.org/2025/sharedtasks.html#somd) (run at [SDP 2025](https://sdproc.org/2025/), co-located with ACL 2025) and focus on entity disambiguation via coreference resolution as an under-investigated problem in this context. More precisely, SOMDi2026 will tackle the following tasks:

**Subtask 1:** Software coreference resolution over gold standard mentions.
Addresses the task based on high-quality (gold standard) mentions of software that are expert-annotated in multiple publications.

**Subtask 2:** Software coreference resolution over predicted mentions.
Addresses the task on software mentions that are automatically extracted using a baseline model, i.e. reflecting a typical information extraction scenario, where upstream pipelines (such as entity and metadata extraction) are imperfect. 

**Subtask 3:** Software coreference resolution at scale. 
For this subtask, we provide predicted mentions of software and metadata at a larger scale. This challenges models to scale effectively, maintain accuracy, and distinguish among an increasingly dense field of similar or overlapping software mentions.

## Important Dates

  * Registration Opens: December 22–23, 2025
  * Train/Test Data Release (All Subtasks): January 10, 2026
  * Competition Phase: January 10 – February 10, 2026 (via Codabench,  link TBA)
  * System Paper & Code Submission Deadline: February 20, 2026
  * Notification of Acceptance: February 28, 2026
  * Camera-Ready Papers Due: March 27, 2026
  * Workshop Date: May 12, 2026



## Shared task organisers: 

* Sharmila Upadhyaya (GESIS Leibniz Institut für Sozialwissenschaften, Germany)

* Wolfgang Otto (GESIS Leibniz Institut für Sozialwissenschaften, Germany)

* Frank Krueger (Wismar University of Applied Sciences, Germany)

* Stefan Dietze (GESIS Leibniz Institut für Sozialwissenschaften, Cologne & Heinrich-Heine-University Düsseldorf, Germany)



## References

[1] Krüger, Frank, et al. *SOMD@NSLP2024: Overview and Insights from the Software Mention Detection Shared Task*. In *Natural Scientific Language Processing and Research Knowledge Graphs*. Springer, 2024. https://doi.org/10.1007/978-3-031-65794-8_17

[2] Schindler, David, et al. *SoMeSci: A 5 Star Open Data Gold Standard Knowledge Graph of Software Mentions in Scientific Articles*. arXiv:2108.09070, 2021. https://arxiv.org/abs/2108.09070

[3] Upadhyaya, Sharmila, et al. *SOMD2025: A Challenging Shared Task for Software Related Information Extraction*. In *Proceedings of the Fifth Workshop on Scholarly Document Processing (SDP 2025)*. ACL, 2025. https://aclanthology.org/2025.sdp-1.13/

