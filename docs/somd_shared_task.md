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

**Task Definition** <br/>
Software is a crucial entity in scientific research, and the identification of such artifacts enables an understanding of provenance and the methods involved in data handling. 
One of the challenges in tracking software usage is that often different names are used for the same software due to abbreviations, geographical differences, or spelling variations (Schindler et al.). The task becomes even harder when considering multiple different documents, containing author specific variations. Hence, this underlines the importance of automatically identifying and disambiguating informally and inconsistently mentioned software. With the following three shared tasks, we aim to advance the resolution of software mentions across multiple documents (cross document coreference resolution). Additionally, we address problems such as a noisy dataset as resulting from automatic prediction and computational complexity affecting runtime as the volume of target texts increases. 


**Subtask 1:** Coreference resolution over gold standard mentions across multiple documents. 
Given all gold-standard annotated software mentions (including metadata and their sentences), the objective of this task is to generate clusters in which each cluster represents mentions referring to the same underlying software.

**Subtask 2:** Coreference resolution over predicted mentions across multiple documents. 
In this subtask, we provide annotated software mentions and their metadata, which are automatically extracted using a baseline model. The challenge is to resolve all co-references to the same software by creating clusters of mentions referring to the same software. This reflects real-world co-reference resolution, where upstream pipelines (such as entity and metadata extraction) are imperfect. 


**Subtask 3:** Coreference resolution over predicted mentions across multiple documents at scale
For this subtask, we provide predicted mentions of software and metadata at a larger scale.  Participants are expected to resolve coreferences to the same software by creating clusters of mentions referring to the same software. Since there are many more entity variants and numerous possible software identities in the provided corpus, this increases the computational runtime challenge for the coreference resolution task. This challenges models to scale effectively, maintain accuracy, and distinguish among an increasingly dense field of similar or overlapping software mentions.


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

