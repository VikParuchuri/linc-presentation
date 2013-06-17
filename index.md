---
title       : An Integrated Framework for the Grading of Freeform Responses
subtitle    : 
author      : Vik Paruchuri/Piotr Mitros
job         : edX
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---


## What is edX?
<img src="assets/img/what_is_edx.png" height="500px" width="700px" class="center"/>

---
## Assessment in MOOCs

### All aspects of a MOOC must scale to thousands

---
<img src="assets/img/ai_pic.png" height="600px" width="700px" class="center"/>

---
<img src="assets/img/mitx_pic.png" height="600px" width="700px" class="center"/>

---
## Remaining Problems

### Short answers
### Forum posts
### Essays
### Pictures
### Videos
### ...

---
## Approaches

### Portfolios
### Artificial intelligence
### Self-assessment
### Peer assessment
### Instructor/TA

---
## Goals

### Maximize accuracy of assessment
### Minimize cost (where grading can be a hassle)

---
## Framework

<img src="assets/img/router.png" height="500px" width="700px" class="center"/>

---
## Self Assessment
* Self assessment allows students to answer a question, see a rubric, and rate themselves.
  * Requires no grading effort from course staff.
  * Particularly valuable in learning sequences where the goal is to learn by constructing knowledge.

---
## AI Assessment
* A computer algorithm scores student submission.
  * Machine Learning (ML) creates a model using 100 course staff graded responses. 
  * This model is used to automatically grade students.
  * For many problems, similar to course staff grading each student individually, but with much less effort.

---
## Peer Assessment
* Peer assessment involves students giving each other scores and feedback
  * Significant pedagogical value for both the student being graded and the grader.
  * Graders first learn how to grade the problem by looking at instructor graded examples.
  * Features such as smart peer matching and user flagging of inappropriate submissions address concerns with previous online peer grading implementations.

---
## Flexible Assessment Types
* Any of the previous 3 assessement types can be used together.
  * A single student response can pass through any combination of graders.
  * For example, a response could be self-assessed, then ML graded. If the two mismatch, peer grading can be used to confirm.

---
## Current Student Problem Interface
Student Submission  |  Student Self-Assesses | External Grader Results
------------- | ------------- | -------------
<img src="assets/img/submission_box_new.png" height="500px" width="300px"/> | <img src="assets/img/self_assessment_rate_new.png" height="500px" width="300px"/> | <img src="assets/img/grader_result_box_new.png" height="500px" width="300px"/>

---
## Questions?
