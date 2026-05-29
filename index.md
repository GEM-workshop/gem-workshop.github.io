---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: GEM at ACL 2026 - Call for Papers
subtitle: The Fifth Generation, Evaluation & Metrics Workshop (GEM)
---

**Event Type:** Call for Papers  
**Conference:** [ACL 2026](https://2026.aclweb.org/program/workshops/)  
**Date:** July 4th, 2026 (All day)  
**Location:** San Diego, California, USA  
**Contact:** gem-workshop-chairs@googlegroups.com

---

## **Overview**

The fifth edition of the Natural Language Generation, Evaluation, and Metrics (GEM) Workshop will be at ACL 2026 in San Diego! 

Evaluation of language models has grown to be a central theme in NLP research, while remaining far from solved. As LMs have become more powerful, errors have become tougher to spot and systems harder to distinguish. Evaluation practices are evolving rapidly—from living benchmarks like Chatbot Arena to LMs being used as evaluators themselves (e.g., LM as judge, autoraters). Further research is needed to understand the interplay between metrics, benchmarks, and human-in-the-loop evaluation, and their impact in real-world settings

## **Topics of Interest**

We welcome submissions related to, but not limited to, the following topics:

* Automatic evaluation of generation systems, including the use of LMs as evaluators  
* Creating evaluation corpora, challenge sets, and living benchmarks  
* Critiques of benchmarking efforts, including contamination, memorization, and validity  
* Evaluation of cutting-edge topics in LM development, including long-context understanding, agentic capabilities, reasoning, and more  
* Evaluation as measurement beyond raw capability, including ideas such as robustness, reliability, and more  
* Multimodal evaluation across text, vision, and other modalities  
* Cost-aware and efficient evaluation methods applicable across languages and scenarios  
* Human evaluation and its role in the era of powerful LMs  
* Evaluation of sociotechnical systems employing large language models  
* Surveys and meta-assessments of evaluation methods, metrics, and benchmarks  
* Best practices for dataset and benchmark documentation  
* Industry applications of the above-mentioned topics, especially internal benchmarking or navigating the gap between academic metrics and real-world impact.

## **Special Tracks**

### **Opinion and Statement Papers Track (New\!)**

We are introducing a special track for opinion and statement papers. These submissions will be presented in curated panel discussions, encouraging open dialogue on emerging topics in evaluation research.

We welcome bold, thought-provoking position papers that challenge conventional wisdom, propose new directions for the field, or offer critical perspectives on current evaluation practices. This track is an opportunity to spark discussion and debate—submissions need not present new empirical results but should offer well-argued viewpoints supported by scientific evidence (e.g. prior studies) that advance our collective thinking about evaluation.

### **ReproNLP** 

The ReproNLP Shared Task on Reproducibility of Evaluations in NLP has been run for six consecutive years (2021–2026).  ReproNLP 2026 will be part of the GEM Workshop at ACL 2026 in San Diego.  It aims to (i) shed light on the extent to which past NLP evaluations have been reproducible, and (ii) draw conclusions regarding how NLP evaluations can be designed and reported in order to increase reproducibility. Participants submit reports for their reproductions of human evaluations from previous NLP literature where they quantitatively assess the degree of reproducibility using methods described in Belz. (2025). More details can be found in the first call for participation for ReproNLP 2026 at [https://repronlp.github.io](https://repronlp.github.io).

## **Workshop Format**

We aim to organize the workshop in an inclusive, highly interactive, and discussion-driven format. Paper presentations will focus on themed poster sessions that allow presenters to interact with researchers from varied backgrounds and similar interests. The workshop will feature panels on emerging topics and multiple short keynotes by leading experts.

### **🎭 GEM Comic-Con Edition\!**

In the spirit of San Diego's famous Comic-Con (July 23-26), this year's GEM will be a special Comic-Con edition\! We encourage participants to embrace creativity\! Whether that’s through themed poster designs, comic-style slides, or dressing up as your favorite evaluation metric personified, we want this year's workshop to be memorable and fun\!

## **Invited Speakers**
Here are our three amazing invited speakers (listed alphabetically).

<img src="{{ '/assets/chris.jpg' | relative_url }}" width="35%" height="35%">

### Chris Callison-Burch (University of Pennsylvania)
**Chris Callison-Burch** is the Raj and Neera Singh Professor of Artificial Intelligence at the University of Pennsylvania, where he directs the online Master's in AI and teaches Penn Engineering's flagship AI course to more than 500 students each fall. In 2026 he received the Lindback Award for Distinguished Teaching, Penn's highest teaching honor. He chairs the advisory board for the Human Language Technology Center of Excellence at Johns Hopkins University. He testified before Congress in 2023 on generative AI and copyright law, and in 2026 participated in the Isaac Asimov Memorial Debate at the American Museum of Natural History, moderated by Neil deGrasse Tyson. He has authored more than 200 publications with over 36,000 citations, and is a Sloan Research Fellow with research support from DARPA, IARPA, NSF, and industry partners including Google, Microsoft, and Amazon.

### Autorubric: A Unified Framework for Rubric-Based LLM Evaluation
**Abstract:** LLM-as-a-judge has become the default for evaluating open-ended generation, but the approach is riddled with silent failure modes, including position bias, verbosity bias, criterion conflation, sycophancy, and run-to-run inconsistency, that corrupt judgments without any visible signal. Mitigations exist, scattered across the LM-as-judge literature and decades of work in psychometrics and educational measurement, but every research group ends up paying a "Reinvention Tax," reimplementing option shuffling, ensemble voting, calibration, and reliability metrics from scratch.

I will present Autorubric, an open-source framework that consolidates these best practices into a single library with opinionated defaults: analytic per-criterion decomposition, mixed criterion types, ensemble judging, length penalties, and a full suite of psychometric reliability metrics. Beyond measurement, Autorubric's mandatory per-criterion explanations function as "textual gradients" for two downstream applications: rubric-guided prompt induction and RL with rubric rewards. Autorubric is available at [](autorubric.org).

<br>

<img src="{{ '/assets/vered.jpg' | relative_url }}" width="20%" height="20%">

### Vered Shwartz (University of British Columbia)
**Vered Shwartz** is an Assistant Professor of Computer Science at the University of British Columbia, a CIFAR AI Chair at the Vector Institute, and the author of "Lost in Automatic Translation: Navigating Life in English in the Age of Language Technologies". Her current research focus is on (1) testing and improving the capabilities of large language models and vision and language models; (2) developing culturally-competent AI; and (3) responsible NLP applications in sensitive domains (e.g., legal, medical). Before joining UBC, she was a postdoctoral researcher at the Allen Institute for AI (AI2) and the University of Washington. Prior to that, she completed her PhD in Computer Science at Bar-Ilan University.

### Follow the Evidence: Diagnosing the What, Where, and Why of Generative Model Failures
**Abstract:** Generative models are improving at a remarkable pace, yet our ability to evaluate them is struggling to keep up. Proprietary, black-box, and frequently updated models limit us to evaluating outputs rather than understanding what shapes them. Meanwhile, as model outputs grow more polished, their errors become more subtle, and we resort to increasingly relying on models themselves as evaluators, with their own blind spots and biases. In this talk, I will discuss three case studies that together reveal the limitations of current evaluation practices. First, I will present Spotlight, a benchmark for fine-grained localization of errors in generated videos. We show that VLMs used as evaluators substantially lag behind humans, missing real errors while hallucinating non-existent ones. Second, I will present Value Drifts, a systematic evaluation that looks inside the LLM post-training process and finds that contrary to common belief, it is supervised fine-tuning — not preference optimization — that most shapes a model's value profile. Third, I will discuss ongoing work on investigating what factors determine whether a multilingual LLM can answer a question about a fact acquired in one language when prompted in another. Across all three case studies, a common thread emerges: the gap between what our evaluations measure and how models may behave "in the wild" is wider than it appears. 

<br>

<img src="{{ '/assets/swabha.png' | relative_url }}" width="35%" height="35%">

### Swabha Swayamdipta (University of Southern California)
**Swabha Swayamdipta** is an Assistant Professor of Computer Science and a co-Associate Director of the Center for AI and Society at the University of Southern California. Her research interests are in natural language processing and machine learning, with a primary interest in the evaluation of generative models of language, understanding the behavior of language models, and designing language technologies for societal good. At USC, Swabha leads the Data, Interpretability, Language and Learning (DILL) Lab. She received her PhD from Carnegie Mellon University, followed by a postdoc at the Allen Institute for AI and the University of Washington. Her work has received outstanding paper awards at EMNLP 2024, ICML 2022, NeurIPS 2021 and ACL 2020. Her research is supported by awards from the NIH, NSF, Apple, the Allen Institute for AI, Intel Labs, the Zumberge Foundation and a WiSE Gabilan Fellowship.

### Small Samples, Big Reveal: What can we learn from limited observations of language model behavior?
**Abstract:** The majority of popular language models today are both large-scale and close-sourced, making studying their behavior quite challenging. This talk tries to answer how much we can learn from limited observations of language model behavior. First, we show that language models can be reliably evaluated using even randomly selected microbenchmarks of a certain size. Second, we use language model outputs, i.e. next-token probability distributions, to build prompt inversion attacks to reveal hidden prompts with high accuracy. These findings highlight the importance of scientific research into large language models without access to large computation resources, while still allowing accountability for the providers, as well as efficient and reliable evaluation.


## **Submission Types**

Submissions can take any of the following forms:

* **Archival Papers:** Original and unpublished work, for all the following tracks—**Main, ReproNLP,** and **Opinion/Statement.** These papers will be **published on the ACL Anthology** in the GEM proceedings, under the ACL 2026 repository. These papers can either be:
  * Direct submissions, which are fully reviewed by the GEM program committe (dual submissions not allowed); or
  * ARR-reviewed papers, which only get a short meta-review based on the existing ARR reviews and meta-review (dual commitments not allowed).
* **Non-Archival Extended Abstracts:** Direct submissions of work already presented/committed or under review at a peer-reviewed venue. This is an excellent opportunity to share recent or ongoing work with the GEM community without precluding future publication. These papers will **not appear in any proceedings**.
* **Findings Papers:** We additionally welcome presentation of relevant papers accepted to the ACL Findings. Please fill in [this form](https://docs.google.com/forms/d/e/1FAIpQLSfyL8EQX5tEbuDlOr-L9GdVNFfYzQ7qwwgS3nriw0qD8SjL4g/viewform?usp=dialog) if you wish to present your Findings paper at GEM! 

## **Submission Guidelines**

* Direct submissions (archival and non archival) to be reviewed should be submitted directly through [OpenReview](https://openreview.net/group?id=aclweb.org/ACL/2026/Workshop/GEM#tab-your-consoles), selecting the appropriate track, and conform to [ACL 2026 style guidelines](https://2026.aclweb.org/calls/main_conference_papers/#paper-submission-details).
* ARR-reviewed papers (archival only) should be submitted through the special [ARR Commitments OpenReview](https://openreview.net/group?id=aclweb.org/ACL/2026/Workshop/GEM_ARR_Commitment#tab-your-consoles).
* **Review requirement (not applicable to ARR-reviewed GEM commitments):** For each submitted paper, authors may be asked to provide 2 reviews (either one author doing 2 reviews, or two authors each doing one review). Please provide the Open Review IDs to one or more reviewer(s) on the submission page.
* All papers should include an Ethics statement and a Limitations section, which do not count towards the page limit. References and Appendices do not count towards the page limit either.
* **Length**.   
  * Archival papers should be within 4–8 pages, and opinion/statement papers should be within 2–4 pages. We make no “Short” or “Long” paper distinctions; we advise authors to tailor their submission length proportional to their contribution.   
  * Extended abstracts should be within 1–2 pages.
  * All accepted papers will be given up to an additional page to address reviewers comments.
* **Opinion/Statement Papers:** These should be titled with the “Position:” prefix.  
* **Dual submission:** Dual submission of archival papers is **not allowed**. Authors interested in presenting work submitted to a different venue should instead use the non-archival extended abstract track.


## **Important Dates (Anywhere on Earth)**

* **March 19, 2026:** Direct paper submission deadline  
* **~~April 9~~ April 15th, 2026:** Pre-reviewed ARR commitment deadline. **Submissions will be accepted until we reach the maximum number of papers we can accommodate, but no later than April 15th AoE.**
* **April 28, 2026:** Notification of acceptance  
* **May 14, 2026:** Camera-ready paper due  
* **June 4, 2026:** Pre-recorded video due (optional, hard deadline)  
* **July 4, 2026:** Workshop at ACL in San Diego

## Program

<div class="table-responsive" markdown="1">
 
| Time | Session/Authors | Title
|:--------|:------|:------|
| 08:55-09:10 | Opening remarks | |
| **09:10-10:20** | **Oral session #1** | |
| 09:10-09:50 | *Invited talk #1 Vered Shwartz* | *Follow the Evidence: Diagnosing the What, Where, and Why of Generative Model Failures* |
| 09:50-10:05 | *Oral presentation #1 (TBD)* | |
| 10:05-10:20 | *Oral presentation #2 (TBD)* | |
| **10:20-10:50** | **Coffee break** | |
| **10:50-11:30** | **Oral session #2** | |
| 10:50-11:15 | *Anya Belz, Craig Thomson, Javier González Corbelle* | *The Shared Task on Reproducibility of Evaluations in NLP (ReproNLP) 2026: Overview and Results* |
| 11:15-11:30 | *Oral presentation #3 (TBD)* | |
| **11:35-12:35** | **Poster session #1** | |
|  | | *All posters, see list of papers below* |
| **12:35-13:55** | **Lunch break** | |
| **13:55-14:55** | **Poster session #2** | |
|  | | *All posters, see list of papers below* |
| **15:00-15:40** | **Oral session #3** | |
| 15:00-15:40 | *Invited talk #2 Swabha Swayamdipta* | *Small Samples, Big Reveal: What can we learn from limited observations of language model behavior?* |
| **15:40-16:10** | **Coffee break** | |
| **16:10-17:20** | **Oral session #4** | |
| 16:10-16:25 | *Oral presentation #4 (TBD)* | |
| 16:25-16:40 | *Oral presentation #5 (TBD)* | |
| 16:40-17:20 | *Invited talk #3 Chris Callison-Burch* | *Autorubric: A Unified Framework for Rubric-Based LLM Evaluation |
| 17:20-17:30 | Closing session* | |

</div>

## **Organizing committee**
* Simon Mille - ADAPT, Dublin City University
* Sebastian Gehrmann - Bloomberg
* Patrícia Schmidtová - Charles University
* Ondřej Dušek - Charles University
* Marzieh Fadaee - Cohere
* Kyle Lo - Allen Institute for AI
* Enrico Santus - Bloomberg
* Gabriel Stanovsky - Hebrew University

## **Contact**

For any questions, please check the workshop page or email the organisers: gem-workshop-chairs@googlegroups.com

