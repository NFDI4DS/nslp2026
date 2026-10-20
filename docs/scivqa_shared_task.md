---
layout: default
title: SciVQA shared task
nav_order: 8
---
<div align="center" style="margin: 0px auto;"> 
<img width="450" height="500" src="SciVQA_2027_logo.gif" alt="scivqa_logo" />
<br/>
<h1> Scientific Visual Question Answering Shared Task (SciVQA 2027)</h1>
</div>

Scientific papers communicate information through unstructured text as well as (semi-)structured figures and tables. 
Jointly reasoning over both modalities benefits downstream applications such as visual question answering (VQA). 
SciVQA 2027 builds on the insights from [SciVQA 2025](https://sdproc.org/2025/scivqa.html) (run at SDP 2025, co-located with ACL 2025), shifting the focus 
toward evaluating the ability of multimodal LLMs to reason over combined modalities (figures, tables, text).

SciVQA 2027 introduces a new set of Computer Science and Computational Linguistics papers, with a total of **1,500** manually annotated QA pairs. 
The shared task features two subtasks:

* **Evidence retrieval**: Given a paper and a question, retrieve candidate evidence (paragraphs and/or images) containing information needed to derive the answer.
* **Answer generation**: Given a paper and a question, generate an answer.

Participants can take part in one or both subtasks. We highly encourage all teams to submit a paper describing the systems to the workshop.

## Competition Platform

The shared task is available on Codabench: TBA

All updates and details on the competition will be published there.

## Dataset

The dataset is available for download on Hugging Face: TBA

## Evaluation 

**Evidence retrieval**: precision, recall, and F1-score (macro and micro).

**Answer generation**: Depending on QA type, exact match, F1-score, or BERTscore and ROUGE-L.

## Important Dates
TBA

## Organizers

* <a href="mailto:ekaterina.borisova@dfki.de">Ekaterina Borisova (DFKI Berlin)</a>
* <a href="mailto:georg.rehm@dfki.de">Georg Rehm (DFKI Berlin)</a>








