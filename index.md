---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: GEM at ACL 2026
subtitle: The Fifth Generation, Evaluation & Metrics Workshop (GEM)
---

**Conference:** [ACL 2026](https://2026.aclweb.org/program/workshops/)  
**Date:** July 4th, 2026 (All day)  
**Location:** San Diego, California, USA  
**Contact:** gem-workshop-chairs@googlegroups.com

---

### **🎭 GEM Comic-Con Edition\!**

In the spirit of San Diego's famous Comic-Con (July 23-26), this year's GEM will be a special Comic-Con edition\! We encourage participants to embrace creativity\! Whether that’s through themed poster designs, comic-style slides, or dressing up as your favorite evaluation metric personified, we want this year's workshop to be memorable and fun\!

## Program

<div class="table-responsive" markdown="1">
 
| Time | Session/Authors | Title
|:--------|:------|:------|
| 08:55-09:10 | Opening remarks | |
| **09:10-10:20** | **Oral session #1** | |
| *09:10-09:50* | *Invited talk #1 Vered Shwartz* | *Follow the Evidence: Diagnosing the What, Where, and Why of Generative Model Failures* |
| *09:50-10:05* | *Oral presentation #Main-81 | |
| *10:05-10:20* | *Oral presentation #Main-99 | |
| **10:20-10:50** | **Coffee break** | |
| **10:50-11:30** | **Oral session #2** | |
| *10:50-11:15* | *Anya Belz, Craig Thomson, Javier González Corbelle* | *The Shared Task on Reproducibility of Evaluations in NLP (ReproNLP) 2026: Overview and Results* |
| *11:15-11:30* | *Oral presentation #Main-65 | |
| **11:35-12:35** | **Poster session #1** | |
|  | | *All posters, see list of papers below* |
| **12:35-13:55** | **Lunch break** | |
| **13:55-14:55** | **Poster session #2** | |
|  | | *All posters, see list of papers below* |
| **15:00-15:40** | **Oral session #3** | |
| *15:00-15:40* | *Invited talk #2 Swabha Swayamdipta* | *Small Samples, Big Reveal: What can we learn from limited observations of language model behavior?* |
| **15:40-16:10** | **Coffee break** | |
| **16:10-17:20** | **Oral session #4** | |
| *16:10-16:25* | *Oral presentation #Main-97 | |
| *16:25-16:40* | *Oral presentation #ARR-4 | |
| *16:40-17:20* | *Invited talk #3 Chris Callison-Burch* | *Autorubric: A Unified Framework for Rubric-Based LLM Evaluation* |
| 17:20-17:30 | Closing session | |

</div>

## **Invited Speakers**
Here are our three amazing invited speakers (by order in the program).

<img src="{{ '/assets/vered.jpg' | relative_url }}" width="20%" height="20%">

### Vered Shwartz (University of British Columbia) - 9:10-9:50 AM
**Vered Shwartz** is an Assistant Professor of Computer Science at the University of British Columbia, a CIFAR AI Chair at the Vector Institute, and the author of "Lost in Automatic Translation: Navigating Life in English in the Age of Language Technologies". Her current research focus is on (1) testing and improving the capabilities of large language models and vision and language models; (2) developing culturally-competent AI; and (3) responsible NLP applications in sensitive domains (e.g., legal, medical). Before joining UBC, she was a postdoctoral researcher at the Allen Institute for AI (AI2) and the University of Washington. Prior to that, she completed her PhD in Computer Science at Bar-Ilan University.

### Follow the Evidence: Diagnosing the What, Where, and Why of Generative Model Failures
**Abstract:** Generative models are improving at a remarkable pace, yet our ability to evaluate them is struggling to keep up. Proprietary, black-box, and frequently updated models limit us to evaluating outputs rather than understanding what shapes them. Meanwhile, as model outputs grow more polished, their errors become more subtle, and we resort to increasingly relying on models themselves as evaluators, with their own blind spots and biases. In this talk, I will discuss three case studies that together reveal the limitations of current evaluation practices. First, I will present Spotlight, a benchmark for fine-grained localization of errors in generated videos. We show that VLMs used as evaluators substantially lag behind humans, missing real errors while hallucinating non-existent ones. Second, I will present Value Drifts, a systematic evaluation that looks inside the LLM post-training process and finds that contrary to common belief, it is supervised fine-tuning — not preference optimization — that most shapes a model's value profile. Third, I will discuss ongoing work on investigating what factors determine whether a multilingual LLM can answer a question about a fact acquired in one language when prompted in another. Across all three case studies, a common thread emerges: the gap between what our evaluations measure and how models may behave "in the wild" is wider than it appears. 

<br>

<img src="{{ '/assets/swabha.png' | relative_url }}" width="35%" height="35%">

### Swabha Swayamdipta (University of Southern California) - 3:00-3:40 PM
**Swabha Swayamdipta** is an Assistant Professor of Computer Science and a co-Associate Director of the Center for AI and Society at the University of Southern California. Her research interests are in natural language processing and machine learning, with a primary interest in the evaluation of generative models of language, understanding the behavior of language models, and designing language technologies for societal good. At USC, Swabha leads the Data, Interpretability, Language and Learning (DILL) Lab. She received her PhD from Carnegie Mellon University, followed by a postdoc at the Allen Institute for AI and the University of Washington. Her work has received outstanding paper awards at EMNLP 2024, ICML 2022, NeurIPS 2021 and ACL 2020. Her research is supported by awards from the NIH, NSF, Apple, the Allen Institute for AI, Intel Labs, the Zumberge Foundation and a WiSE Gabilan Fellowship.

### Small Samples, Big Reveal: What can we learn from limited observations of language model behavior?
**Abstract:** The majority of popular language models today are both large-scale and close-sourced, making studying their behavior quite challenging. This talk tries to answer how much we can learn from limited observations of language model behavior. First, we show that language models can be reliably evaluated using even randomly selected microbenchmarks of a certain size. Second, we use language model outputs, i.e. next-token probability distributions, to build prompt inversion attacks to reveal hidden prompts with high accuracy. These findings highlight the importance of scientific research into large language models without access to large computation resources, while still allowing accountability for the providers, as well as efficient and reliable evaluation.

<img src="{{ '/assets/chris.jpg' | relative_url }}" width="35%" height="35%">

### Chris Callison-Burch (University of Pennsylvania) - 4:40-5:20 PM
**Chris Callison-Burch** is the Raj and Neera Singh Professor of Artificial Intelligence at the University of Pennsylvania, where he directs the online Master's in AI and teaches Penn Engineering's flagship AI course to more than 500 students each fall. In 2026 he received the Lindback Award for Distinguished Teaching, Penn's highest teaching honor. He chairs the advisory board for the Human Language Technology Center of Excellence at Johns Hopkins University. He testified before Congress in 2023 on generative AI and copyright law, and in 2026 participated in the Isaac Asimov Memorial Debate at the American Museum of Natural History, moderated by Neil deGrasse Tyson. He has authored more than 200 publications with over 36,000 citations, and is a Sloan Research Fellow with research support from DARPA, IARPA, NSF, and industry partners including Google, Microsoft, and Amazon.

### Autorubric: A Unified Framework for Rubric-Based LLM Evaluation
**Abstract:** LLM-as-a-judge has become the default for evaluating open-ended generation, but the approach is riddled with silent failure modes, including position bias, verbosity bias, criterion conflation, sycophancy, and run-to-run inconsistency, that corrupt judgments without any visible signal. Mitigations exist, scattered across the LM-as-judge literature and decades of work in psychometrics and educational measurement, but every research group ends up paying a "Reinvention Tax," reimplementing option shuffling, ensemble voting, calibration, and reliability metrics from scratch.

I will present Autorubric, an open-source framework that consolidates these best practices into a single library with opinionated defaults: analytic per-criterion decomposition, mixed criterion types, ensemble judging, length penalties, and a full suite of psychometric reliability metrics. Beyond measurement, Autorubric's mandatory per-criterion explanations function as "textual gradients" for two downstream applications: rubric-guided prompt induction and RL with rubric rewards. Autorubric is available at [](autorubric.org).

<br>

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

