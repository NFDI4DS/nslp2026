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

  * Registration Opens: January 14, 2025
  * Train/Test Data Release (All Subtasks): January 20, 2026
  * Competition Phase: January 20 – February 20, 2026 (via Codabench)
  * System Paper & Code Submission Deadline: February 27, 2026
  * Notification of Acceptance: March 10, 2026
  * Camera-Ready Papers Due: March 27, 2026
  * Workshop Date: May 12, 2026


## Participation
Participants can take part in one or more of the three subtasks independently. Each subtask are hosted on the same competition platform but as separate competition.

  ***Registration***
  
  To participate, teams must register on the competition platform via the Participation Link:
  * <a href="https://www.codabench.org/competitions/12684/?secret_key=4afda676-dd52-4172-af45-ea0dafe6d471">Subtask1</a>
  * <a href="https://www.codabench.org/competitions/12685/?secret_key=fbf08109-f885-4a99-881a-0cb0f6a7003f">Subtask2</a>
  * <a href="https://www.codabench.org/competitions/12686/?secret_key=01b509f4-1e7d-46a5-8dde-027dccfde384">Subtask3</a>
  
  After registration, participants will gain access to:
  * The training and Test data
  * Submission instructions for each subtask
  * The evaluation leaderboard(s)

Participation is open to both academic and industry teams. Teams may consist of one or more members.

## Dataset
Dataset has been released on the Codabench Competition page.
* <a href="https://www.codabench.org/competitions/12684/?secret_key=4afda676-dd52-4172-af45-ea0dafe6d471">Subtask1</a>
* <a href="https://www.codabench.org/competitions/12685/?secret_key=fbf08109-f885-4a99-881a-0cb0f6a7003f">Subtask2</a>
* <a href="https://www.codabench.org/competitions/12686/?secret_key=01b509f4-1e7d-46a5-8dde-027dccfde384">Subtask3</a>


##  System Paper Submission Guidelines

  <p>
    The SOMD 2026 Shared Task, organized as part of the NSLP 2026 workshop, 
    invites submissions of <strong>system description papers</strong> from participating teams.
  </p>

  <h3>Eligibility</h3>
  <p>
    System papers must describe participation in one or more of the SOMD 2026 subtasks:
  </p>
  <ul>
    <li><strong>Subtask 1:</strong> Cross-document coreference resolution over gold-standard mentions</li>
    <li><strong>Subtask 2:</strong> Cross-document coreference resolution over predicted mentions</li>
    <li><strong>Subtask 3:</strong> Large-scale cross-document coreference resolution over predicted mentions</li>
  </ul>
  <p>
    We will not accept work that is under review or has already been published in or accepted 
    for publication in a journal, another conference, or another workshop.
  </p>

  <h3>Paper Length</h3>
  <ul>
    <li><strong>Long papers:</strong> up to 8 pages (excluding references and appendix)</li>
    <li><strong>Short papers:</strong> up to 4 pages (excluding references and appendix)</li>
  </ul>
  <p>
    An optional appendix of up to 2 pages is allowed. Reviewers are not required to review 
    the appendix, and all papers must be self-contained.
  </p>

  <h3>Review Process</h3>
  <p>
    <strong>System paper submissions are NOT anonymous.</strong>
  </p>
  <ul>
    <li>Author names and affiliations must be included in the submission.</li>
    <li>The review process will be single-blind.</li>
    <li>Submissions do not need to be anonymized.</li>
  </ul>
  <p>
    Please note that this differs from the regular NSLP workshop submissions, 
    which follow a double-blind review process.
  </p>

  <h3>Formatting Requirements</h3>
  <ul>
    <li>Submissions must be in PDF format.</li>
    <li>Papers must follow the official LREC 2026 style guidelines.</li>
    <li>Templates (LaTeX and Word) are available on the LREC 2026 website.</li>
  </ul>

  <h3>Proceedings</h3>
  <p>
    Accepted system papers will be published as part of the NSLP 2026 workshop proceedings, 
    included in the LREC 2026 proceedings in the ACL Anthology (Full Open Access).
  </p>

  <h3>Submission Platform</h3>
  <p>
    All system papers must be submitted via:
  </p>
  <p>
    <strong>START (Softconf):</strong><br>
    <a href="https://softconf.com/lrec2026/NSLP2026/" target="_blank">
      https://softconf.com/lrec2026/NSLP2026/
    </a>
  </p>
  <p>
    Please select the appropriate <strong>SOMD 2026 Shared Task – System Paper</strong> track during submission.
  </p>

  <h3>Registration Requirement</h3>
  <p>
    At least one author of each accepted system paper must register for the workshop 
    and present the work.
  </p>

  <h3>Important Dates</h3>
  <ul>
    <li><strong>System Paper & Code Submission Deadline:</strong> February 27, 2026</li>
    <li><strong>Notification of Acceptance:</strong> March 10, 2026</li>
    <li><strong>Camera-Ready Deadline:</strong> March 27, 2026</li>
    <li><strong>Workshop Date:</strong> May 12, 2026</li>
  </ul>
</section>
If you want, I can also provide:

A more compact version (for small webpage space)

A visually styled version with simple CSS

Or a version adapted for Codabench competition page


You said:
and add easy chair link of submission tba

ChatGPT said:
Here is the updated HTML section, now including an EasyChair submission link (TBA) in addition to the START link. You can later replace the # with the real EasyChair URL.

<section id="somd2026-system-paper-submission">
  <h2>SOMD 2026 Shared Task – System Paper Submission Guidelines</h2>

  <p>
    The SOMD 2026 Shared Task, organized as part of the NSLP 2026 workshop, 
    invites submissions of <strong>system description papers</strong> from participating teams.
  </p>

  <h3>Eligibility</h3>
  <p>
    System papers must describe participation in one or more of the SOMD 2026 subtasks:
  </p>
  <ul>
    <li><strong>Subtask 1:</strong> Cross-document coreference resolution over gold-standard mentions</li>
    <li><strong>Subtask 2:</strong> Cross-document coreference resolution over predicted mentions</li>
    <li><strong>Subtask 3:</strong> Large-scale cross-document coreference resolution over predicted mentions</li>
  </ul>
  <p>
    We will not accept work that is under review or has already been published in or accepted 
    for publication in a journal, another conference, or another workshop.
  </p>

  <h3>Paper Length</h3>
  <ul>
    <li><strong>Long papers:</strong> up to 8 pages (excluding references and appendix)</li>
    <li><strong>Short papers:</strong> up to 4 pages (excluding references and appendix)</li>
  </ul>
  <p>
    An optional appendix of up to 2 pages is allowed. Reviewers are not required to review 
    the appendix, and all papers must be self-contained.
  </p>

  <h3>Review Process</h3>
  <p>
    <strong>System paper submissions are NOT anonymous.</strong>
  </p>
  <ul>
    <li>Author names and affiliations must be included in the submission.</li>
    <li>The review process will be single-blind.</li>
    <li>Submissions do not need to be anonymized.</li>
  </ul>
  <p>
    Please note that this differs from the regular NSLP workshop submissions, 
    which follow a double-blind review process.
  </p>

  <h3>Formatting Requirements</h3>
  <ul>
    <li>Submissions must be in PDF format.</li>
    <li>Papers must follow the official LREC 2026 style guidelines.</li>
    <li>Templates (LaTeX and Word) are available on the LREC 2026 website.</li>
  </ul>

  <h3>Proceedings</h3>
  <p>
    Accepted system papers will be published as part of the NSLP 2026 workshop proceedings, 
    included in the LREC 2026 proceedings in the ACL Anthology (Full Open Access).
  </p>

  <h3>Submission Platform</h3>
  <p>
    System papers can be submitted via:
  </p>

  <p>
    <strong>EasyChair (System Paper Track):</strong><br>
    <a href="#" target="_blank">Submission link – TBA</a>
  </p>

 

  <p>
    Please select the appropriate <strong>SOMD 2026 Shared Task – System Paper</strong> track during submission.
  </p>

  <h3>Registration Requirement</h3>
  <p>
    At least one author of each accepted system paper must register for the workshop 
    and present the work.
  </p>

  <h3>Important Dates</h3>
  <ul>
    <li><strong>System Paper & Code Submission Deadline:</strong> February 27, 2026</li>
    <li><strong>Notification of Acceptance:</strong> March 10, 2026</li>
    <li><strong>Camera-Ready Deadline:</strong> March 27, 2026</li>
    <li><strong>Workshop Date:</strong> May 12, 2026</li>
  </ul>
</section>
## Shared task organisers: 

* Sharmila Upadhyaya (GESIS Leibniz Institut für Sozialwissenschaften, Germany)

* Wolfgang Otto (GESIS Leibniz Institut für Sozialwissenschaften, Germany)
  
* Julia Matela (Wismar University of Applied Sciences, Germany)

* Frank Krueger (Wismar University of Applied Sciences, Germany)

* Stefan Dietze (GESIS Leibniz Institut für Sozialwissenschaften, Cologne & Heinrich-Heine-University Düsseldorf, Germany)



## References

[1] Krüger, Frank, et al. *SOMD@NSLP2024: Overview and Insights from the Software Mention Detection Shared Task*. In *Natural Scientific Language Processing and Research Knowledge Graphs*. Springer, 2024. https://doi.org/10.1007/978-3-031-65794-8_17

[2] Schindler, David, et al. *SoMeSci: A 5 Star Open Data Gold Standard Knowledge Graph of Software Mentions in Scientific Articles*. arXiv:2108.09070, 2021. https://arxiv.org/abs/2108.09070

[3] Upadhyaya, Sharmila, et al. *SOMD2025: A Challenging Shared Task for Software Related Information Extraction*. In *Proceedings of the Fifth Workshop on Scholarly Document Processing (SDP 2025)*. ACL, 2025. https://aclanthology.org/2025.sdp-1.13/

