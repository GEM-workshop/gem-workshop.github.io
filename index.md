---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: GEM at ACL 2026 - Schedule
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
| *09:10-09:50* | *Invited talk #1 Vered Shwartz* | Follow the Evidence: Diagnosing the What, Where, and Why of Generative Model Failures |
| *09:50-10:05* | *Erfan Nourbakhsh, Mohammad Sadegh, Seyed Amir, Khoa Nguyen, John Quarles, Mimi Xie, Rocky Slavin* | Are LLM Benchmarks Already Contaminated? A Systematic Review of Contamination Detection Methods | |
| *10:05-10:20* | *Craig Thomson, Javier González, Anya Belz* | Process Standardisation for Human Evaluation of NLP System Outputs |
| **10:20-10:50** | **Coffee break** | |
| **10:50-11:30** | **Oral session #2** | |
| *10:50-11:15* | *Anya Belz, Craig Thomson, Javier González Corbelle* | The Shared Task on Reproducibility of Evaluations in NLP (ReproNLP) 2026: Overview and Results |
| *11:15-11:30* | *Davan Harrison, Marilyn Walker* | Cross-Domain Semantic Fidelity Evaluation for Meaning-to-Text Generation |
| **11:35-12:35** | **Poster session #1** | |
|  | *See list of authors below* | *All posters, see list of papers below* |
| **12:35-13:55** | **Lunch break** | |
| **13:55-14:55** | **Poster session #2** | |
|  | *See list of authors below* | *All posters, see list of papers below* |
| **15:00-15:40** | **Oral session #3** | |
| *15:00-15:40* | *Invited talk #2 Swabha Swayamdipta* | Small Samples, Big Reveal: What can we learn from limited observations of language model behavior? |
| **15:40-16:10** | **Coffee break** | |
| **16:10-17:20** | **Oral session #4** | |
| *16:10-16:25* | *Avni Mittal, Rauno Arike* | C2-Faith: Benchmarking LLM Judges for Causal and Coverage Faithfulness in Chain-of-Thought Reasoning |
| *16:25-16:40* | *Zefang Liu, Yinzhu Quan* | EconWebArena: Benchmarking Autonomous Agents on Economic Tasks in Realistic Web Environments |
| *16:40-17:20* | *Invited talk #3 Chris Callison-Burch* | Autorubric: A Unified Framework for Rubric-Based LLM Evaluation |
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

## **Posters: 11:35-12:35 and 13:55-14:55**
- DISCO: Diversifying Sample Condensation for Efficient Model Evaluation. *Alexander Rubinstein, Benjamin Raible, Martin Gubri, Seong Joon.*
- CoSy: Conversational Synthesis for Grounded Question Answering. *Patrick Huber, Arash Einolghozati, Rylan Conway, Kanika Narang, Matt Smith, Waqar Nayyar, Adithya Sagar, Ahmed A, Akshat Shrivastava.*
- Position: Toward a Metric Typology for Language Model Evaluation. *Jasper Kyle.*
- VAIDYA: Validated Agents for Intelligent Diagnosis and Yielded Analysis. *Kalash Shah, Gautam Bhutani, Rohitaswa Sarbhangia, J Snehan.*
- Self-Anchoring Calibration Drift in Large Language Models: How Multi-Turn Conversations Reshape Model Confidence. *Harshavardhan .*
- Temporal Tokenization Strategies for Event Sequence Modeling with Large Language Models. *Zefang Liu, Nam H, Yinzhu Quan, Shi-Xiong Zhang.*
- “Be My Cheese?”: Cultural Nuance Benchmarking for Machine Translation in Multilingual LLMs. *Madison Van, Casey Ford, Riley VanMeter, Jennifer Barajas, Cory Holland.*
- Position: What Are We Measuring? Rethinking Evaluation in Natural Language Generation. *Wajdi Zaghouani.*
- Component Transfer Can Exceed Full Model Performance: Investigating Post-Trained Mixture-of-Experts. *Rabin Tiwari.*
- CAMEL: Learning Community-Aligned Metrics and Weights for LLM Evaluation. *Ji Yong, Bumsoo Kang, June Yong, Youngsoo Jang, Chang Liu, Moontae Lee.*
- Reassessing Extractive QA Datasets at Scale: LLM-as-a-Judge and In-Depth Analyses. *Xanh Ho, Jiahao Huang, Florian Boudin, Akiko Aizawa.*
- IndicMMLU-Pro: Benchmarking Indic Large Language Models on Multi-Task Language Understanding. *Sankalp Jajee, Ashutosh Kumar, Nikunj Kotecha, Vinija Jain, Aman Chadha, Sreyoshi Bhaduri.*
- Identifying Where Large Language Models Struggle in Answering Complex Questions. *Xanh Ho, Florian Boudin, Saku Sugawara, Khoa Duong, Akiko Aizawa.*
- More Yap Less Meaning: Uncovering Self-Improvement Behavior in SLMs. *Marina Igitkhanian, Erik Arakelyan.*
- Reinforced Agent: Inference-Time Feedback for Tool-Calling Agents. *Anh Ta, Shahin Shayandeh, Junjie Zhu.*
- Reviewing Only 1/10 of Submissions: Efficient Human-in-the-Loop Discovery for Approach-Aware LLM Grading. *Jinglun Zhao, Zijian Zhang, Jiaxuan Gao, Yi Wu.*
- DETOUR: An Interactive Benchmark for Dual-Agent Search and Reasoning. *Siyan Li, Darshan Girish, Anand Kannappan, Rebecca Qian.*
- Evaluating Style-Personalized Text Generation: Challenges and Directions. *Anubhav Jangra, Bahareh Sarrafzadeh, Silviu Cucerzan, Adrian de, Sujay Kumar.*
- RE-AD: Real-Time Requirement Adherence for Data Labeling. *Siddarth Malreddy, Ishan Nigam, Akshay Arora, Nikhil Mittal, Subrat Sahu.*
- Lost in Space: Finding the Right Tokens for Structured Output. *Sil Hamilton, David Mimno.*
- An Empirical Study of LLM-as-a-Judge: How Design Choices Impact Evaluation Reliability. *Yusuke Yamauchi, Taro Yano, Masafumi Oyamada.*
- Consensus Group Relative Policy Optimization for Distilling Minimum Bayes Risk Decoding. *Yuki Ichihara, Yuu Jinnai, Kaito Ariu, Eiji Uchibe.*
- Capturing Epistemic Uncertainty in LLM-Based Soft Labeling. *Yanru Jiang, Siyu Liang.*
- Mind the Gap... or Not? How Translation Errors and Evaluation Details Skew Multilingual Results. *Jan-Thorsten Peter, David Vilar, Tobias Domhan, Dan Malkin, Markus Freitag.*
- MCJudgeBench: A Benchmark for Constraint-Level Judge Evaluation in Multi-Constraint Instruction Following. *Jaeyun Lee, Junyoung Koh, Zeynel Tok, Hunar Batra, Ronald Clark.*
- MedAct: Removing the Human Bottleneck in Benchmarking Clinical LLM Safety. *Arjun Krishna, Brian Pridgen, Max Silverstein.*
- Response Content Units: Evaluating Completeness and Proactiveness in Medical Open-Response Question Answering. *Yongsin Park, Wen-wai Yim, Emma McKibbin, Asma Ben, Fei Xia.*
- Position: Evaluation Scores Are Perishable Knowledge Claims. *Sankalp Gilda, Shlok Gilda.*
- LFQA-HP-1M: A Large-Scale Human Preference Dataset for Long-Form Question Answering. *Rafid Ishrak, FAHMID SHAHRIAR, Sagnik Ray.*
- NanoFlux: Adversarial Dual-LLM Evaluation and Distillation for Multi-Domain Reasoning. *Raviteja Anantha, Soheil Hor, Teodor Nicola, Layne C.*
- Evaluating the Reliability of LLMs in Faithfully Updating Text: An Empirical Study. *Ayan Datta, Paheli Bhattacharya, Rishabh Gupta.*
- Position: A Semiotic-Hermeneutic Approach to Evaluating Meaning in LLM Summaries via the Inductive Conceptual Rating Metric. *Natalie Perez, Aman Chadha, Sreyoshi Bhaduri.*
- Not All Tokens Are Equal: Per-Dimension Top-K Pooling for Adversarially Robust BERT Classification. *Manoranjan Dash, Shivam Anand, Shanay Sheth, Pranav Shinde.*
- Near-Miss: Latent Policy Failure Detection in Agentic Workflows. *Ella Rabinovich, David Boaz, Naama Zwerdling, Ateret Anaby.*
- Evaluating Counterfactual Strategic Reasoning in Large Language Models. *Dimitrios Georgousis, Maria Lymperaiou, Angeliki Dimitriou, Giorgos Filandrianos, Giorgos Stamou.*
- A Psychology-based Unified Dynamic Framework for Curriculum Learning. *Guangyu Meng, John P..*
- Speculative Refinement: A Hybrid Autoregressive Diffusion Decoding Strategy and Its Behavior Across Benchmarks. *Aditi Gupta, Neel Mishra, Kushagra Trivedi, Pawan Kumar.*
- SAUCE: Summary Analysis Using Conversation Entailment. *Man-Ling Sung, Hemanth Kandula, Jeff Ma, William Hartmann, Matthew Snover.*
- Evaluating ASR Quality at Scale on TV Entertainment Platforms. *Adeep Hande, Kishorekumar Sundararajan, Yidnekachew Endale, Akshatha Bapu, Sachin Dabral, Dawn Reed, Michael Pereira.*
- Teaching Values to Machines: Simulating Human-Like Value-Behavior Relationships in LLMs. *Asaf Yehudai, Naama Rozen, Ariel Gera.*
- Fine-Tuning vs. RAG for Multi-Hop Question Answering with Novel Knowledge. *Zhuoyi Yang, Yurun song, Kyler G., Iftekhar Ahmed, Ian Harris.*
- MHGraphBench: Knowledge Graph-Grounded Benchmarking of Mental Health Knowledge in Large Language Models. *Weixin Liu, Congning Ni, Shelagh A., Susannah L., Murat Kantarcioglu, Bradley A., Zhijun Yin.*
- A Progressive Evaluation Framework for Multicultural Analysis of Story Visualization. *Janak Kapuriya, Ali Hatami, Paul Buitelaar.*
- Is GraphRAG Needed? From Basic RAG to Graph-/Agentic Solutions with Context Optimization. *Long Chen, Ryan Razkenari, Yuxuan Zhou, Yuan Tian, Rahul Ghosh, Venkatesh Pappakrishnan, Disha Ahuja, Vidya Sagar.*
- Cross-Domain Semantic Fidelity Evaluation for Meaning-to-Text Generation. *Davan Harrison, Marilyn Walker.*
- E-star 12B: Reliable Rubric-Following and Domain-Adaptive SLM Evaluator for Korean Industrial Settings. *Yonghoon Kwon, Heondeuk Lee, Barom Kang.*
- Pressure-Testing Deception Probes in LLMs: Scaling, Robustness, and the Geometry of Deceptive Representations. *Sachin Kumar.*
- S-GRADES - Studying Generalization of Student Response Assessments in Diverse Evaluative Settings. *Tasfia Seuti, Sagnik Ray.*
- Sycophancy Negatively Affects LLM-as-a-Judge in Conflict Evaluation. *Naghmeh Farzi, Laura Dietz, Samuel Carton.*
- Concord: An Agreement-Aware Multi-Adjudication Pipeline for LLM Evaluation. *Tyler Bliss, Mahit Verma, Neil Iyer-Singh, Subrata Biswas, S. A., Bashima Islam.*
- ScienceMeter: Tracking Scientific Knowledge Updates in Language Models. *Yike Wang, Shangbin Feng, Yulia Tsvetkov, Hannaneh Hajishirzi.*
- The Silent Vote: Improving Zero-Shot LLM Reliability by Aggregating Semantic Neighborhoods. *Sanket Badhe, Priyanka Tiwari, Deep Shah.*
- From XAI to Stories: A Factorial Study of LLM-Generated Explanation Quality. *Fabian Lukassen, Jan Herrmann, Christoph Weisser, Benjamin Säfken, Thomas Kneib.*
- Are LLM Benchmarks Already Contaminated? A Systematic Review of Contamination Detection Methods. *Erfan Nourbakhsh, Mohammad Sadegh, Seyed Amir, Khoa Nguyen, John Quarles, Mimi Xie, Rocky Slavin.*
- RBCorr: Response Bias Correction in Language Models. *Om Bhatt, Anna A.*
- Exploring Coherence of LLMs in Multilingual Question Answering. *Stefano Campese, Ivano Lauriola.*
- Beyond Consensus: Evaluating Multi-Agent LLM Debates through a Deliberative Democracy Framework. *Priya Pitre, Gaurav Srivastava, Lu Zhang, Le Wang, Naren Ramakrishnan, Xuan Wang.*
- Token Cost Inequality: Measuring Tokenization Disparities Across Scripts in Roman Urdu and Urdu. *Waleed Jamil, Saima Rafi, Yanchao Yu.*
- Semantic vs. Structural Signals: Log-Probability and LLM-as-a-Judge for Reference-Free Code Evaluation. *Dmitriy Fedrushkov, Yulong He, Ivan Smirnov, Artem Aliev, Sergey Kovalchuk.*
- Statistically Reliable LLM-Based Ranking Evaluation via Prediction-Powered Inference. *Abhishek Divekar.*
- Stability vs. Manipulability: Evaluating Robustness Under Post-Decision Interaction in LLM Judges. *Srimonti Dutta, Akshata Kishore.*
- Permutation-Consensus Listwise Judging for Robust Factuality Evaluation. *Tianyi Huang, Nathan Huang, Justin Tang, Wenqian Chen, Elsa Fan.*
- MedFact: Benchmarking the Fact-Checking Capabilities of Large Language Models on Chinese Medical Texts. *Ivy He, Yangmin Huang, Qianyun Du, Xiangying Zhou, Zhiyang He, Jiaxue Hu, Xiaodong Tao, Lixian Lai.*
- Position: Scores Without Context? Rethinking the Role of Evaluation in the Era of LLMs. *Jiawei Zhou.*
- Early-Token Confidence Predicts Reasoning Quality in Multi-Agent LLM Debate. *Ali Keramati, Justin Cheok, Jacob Horne, Mark Warschauer.*
- Complex-IF and Beyond: Expert Rubrics for RLVR. *Sushant Mehta.*
- C2-Faith: Benchmarking LLM Judges for Causal and Coverage Faithfulness in Chain-of-Thought Reasoning. *Avni Mittal, Rauno Arike.*
- Evaluating Multilingual Sentiment Classifiers Using an LLM-Annotated Wikipedia Benchmark. *Milena Stróżyna, Włodzimierz Lewoniewski, Izabela Czumałowska.*
- Process Standardisation for Human Evaluation of NLP System Outputs. *Craig Thomson, Javier González, Anya Belz.*
- ReproHum #0124-03: Reproducing Human Scores on Neural REG Models. *Maurice Langner.*
- ReproHum #0866-04: Variability in Human Judgments of Sociopolitical Acceptability Across Studies. *Rui Fan, Guanyi Chen.*
- ReproNLP 2026: A Third Replication of the Human Evaluation of a QAG System for Children’s Storybooks. *Marcel Mroczek, Chiara Albarello, Paul-Emmanuel Floch, Maciej Gawinecki.*
- ReproHum 0031–01: Reproducing a Human Readability Evaluation for Question–Answer Generation Systems. *Manuela Hürlimann, Mark Cieliebak.*
- Do Nugget-Based Evaluation Patterns Generalize to List-QA?. *MohammadJavad Ardestani, Ehsan Kamalloo, Davood Rafiei.*
- ReproHum: #0033-05: Human Evaluation Report on "Generating Scientific Definitions with Controllable Complexity". *Ines Arous, Jackie Chi.*
- The Shared Task on Reproducibility of Evaluations in NLP (ReproNLP) 2026: Overview and Results. *Anya Belz, Craig Thomson, Javier González.*
- ReproHum #0669-08: Reproducing a Recipe for Arbitrary Text Style Transfer with LLMs. *Saad Mahamood.*
- Language Modeling for the Future of Finance: A Survey into Metrics, Tasks, and Data Opportunities. *Nikita Tatarinov, Siddhant Sukhani, Agam Shah, Sudheer Chava.*
- WildIFEval: Instruction Following in the Wild. *Gili Lior, Asaf Yehudai, Ariel Gera, Liat Ein-Dor.*
- EconWebArena: Benchmarking Autonomous Agents on Economic Tasks in Realistic Web Environments. *Zefang Liu, Yinzhu Quan.*
- ISO-Bench: Benchmarking Multimodal Causal Reasoning in Visual–Language Models through Procedural Plans. *Ananya Sadana, Yash Kumar, Jiawei Zhou.*
- Text Analytics Evaluation Framework: A Case Study on LLMs and Social Media. *Yuefeng Shi, Nedjma Ousidhoum, Jose Camacho-Collados.*
- Teaching Values to Machines: Simulating Human-Like Behavior in LLMs. *Asaf Yehudai, Naama Rozen, Ariel Gera.*
- MetaGraph: A Large-Scale Meta-Analysis of GenAI in Financial NLP (2022–2025). *Paolo Pedinotti, Peter Baumann, Nathan Jessurun, Leslie Barrett, Enrico Santus.*
- When Users Are Happy but Agents Are Wrong: Multi-Dimensional Evaluation of Tool-Augmented Dialogue. *Tanya Shourya, Yingfan Wang, Zhaoyi Joey, Shamik Roy, Vinayshekhar Bannihatti, Rashmi Gangadharaiah.*
- Tool-Aware Planning for Contact-Center Analytics: Evaluating LLMs through Lineage-Guided Query Decomposition. *Varun Nathan, Shreyas Guha, Ayush Kumar.*
- TSAQA: Time Series Analysis Question And Answering Benchmark. *Baoyu Jing, Sanhorn Chen, Lecheng Zheng, Boyu Liu, Zihao Li, Jiaru Zou, Tianxin Wei, Zhining Liu, Zhichen Zeng, Ruizhong Qiu, Xiao Lin, Yuchen Yan, Dongqi Fu, Jingchao Ni, Jingrui He, Hanghang Tong.*
- Who Endorsed It? Measuring Authority Bias Across Expertise Levels in Language Models. *Priyanka Mary, Emil Joswin, Shankar Venkitachalam.*
- Reference Games as a Testbed for the Alignment of Model Uncertainty and Clarification Requests. *Manar Ali, Judith Sieker, Sina Zarrieß, Hendrik Buschmeier.*
- Mapping Out the NLP Evaluation Landscape with a Standard Taxonomy of Quality Criteria. *Anya Belz, Simon Mille, Craig Thomson.*

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

