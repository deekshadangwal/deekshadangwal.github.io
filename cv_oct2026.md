---
name: Deeksha Dangwal
header:
  - text: <span class="iconify" data-icon="tabler:mail"></span> deekshadangwal@gmail.com
    link: mailto:deekshadangwal@gmail.com
  - text: <span class="iconify" data-icon="academicons:google-scholar"></span> GScholar
    link: https://scholar.google.com/citations?user=11KckrAAAAAJ&hl=en
  - text: <span class="iconify" data-icon="charm:person"></span> deekshadangwal.com
    link: https://www.deekshadangwal.com
---

<!-- colors used:  -->
<!-- Dark blue: #043E95 -->
<!-- Green: #43912B -->
<!-- yellow: #EE8732 -->
<!-- purple: #9C5BDE -->

## Research Interests

**AI Safety and Alignment, ML Systems, Security and Privacy**

I am a systems researcher working on AI safety. My background is in computer architecture and hardware security, and I study where safety mechanisms should be enforced in the training stack. Prior work has shown that safety training in open-weight models can be undone with a small amount of fine-tuning; my current work develops a threat model for this setting and monitors that operate on model weights during fine-tuning. My work in computer architecture, privacy, and secure computation appeared in ISCA, ASPLOS, PLDI, FPL, BMVC, and TMLR.
My SoK on hardware-software-security codesign was **cited in the US National Strategy on Microelectronics Research**, I am a **Rising Stars in EECS** alumna, and trace wringing was an **IEEE Micro Top Pick**.

## Education
**Doctor of Philosophy, Computer Science**
  ~ **03/2022**

University of California, Santa Barbara

Thesis: [**"A System-level Framework for Privacy"**](https://www.proquest.com/docview/2923629631?sourcetype=Dissertations%20&%20Theses)
advised by **Prof. Timothy Sherwood**

\\[6px]

**Master of Science, Electrical and Computer Engineering**
  ~ **09/2016**

University of California, Santa Barbara

\\[6px]

**Bachelor of Engineering, Instrumentation and Electronics**
  ~ **05/2014**

Ramaiah Institute of Technology, Bangalore, India

## Awards and Honors
**2026 ERA:AI Fellowship in Technical AI Governance, Cambridge, UK** _(Top 0.5% of applicants)_
  ~ **2026**

\\[6px]
**Our paper, "SoK: Opportunities for Software-Hardware-Security Codesign for Next-Generation Secure Computing"** (HASP'20) appears in the [*United States National Strategy on Microelectronics Research*](https://www.nitrd.gov/pubs/National-Strategy-on-Microelectronics-Research-March-2024.pdf)
  ~ **2024**

\\[6px]

**Runner-up**, UCSB Grad Slam Competition
  ~ **2021**

\\[6px]

**Rising Stars in EECS**, UC Berkeley
  ~ **2020**

\\[6px]

**IEEE Micro Top Pick**, Trace Wringing for Program Trace Privacy
  ~ **2020**

\\[6px]

**Fiona and Michael Goodchild Graduate Mentoring Award**, UCSB Graduate Division
  ~ **2020**

\\[6px]

**Outstanding Graduate Student Award**, Department of Computer Science, UCSB
  ~ **2020**

<!-- \\[6px]

**Second Place**, NXP Embedded Design Challenge
  ~ **2015**

\\[6px] -->

## Experience

**Fellow**, _MATS Research, Berkeley, CA_
  ~ **09/2026 - Present**

- <u>Compute Verification</u>: Designing and empirically evaluating software-based compute verification protocols (memory-state challenges, subsampled zero-knowledge proofs) that bound undeclared GPU workloads without trusted hardware <u>_(Mentored by James Petrie, Future of Life Institute)_</u>

\\[6px]
**Research Fellow**, _ERA:AI Fellowship in Technical AI Governance, Cambridge, UK_
  ~ **07/2026 - Present**

- <u>Training-Time Safety Monitoring</u>: Developed a defense against fine-tuning attacks that strip safety behavior from open-weight LLMs. Built a testbed of over 200 controlled fine-tuning runs spanning four open reasoning model families, from 20B to 1T parameters, and designed a monitor that watches only the weight updates as training runs. The monitor catches safety-removal with AUROC 0.97 to 1.00 before the model's behavior collapses and transfers across model families and training objectives with no per-model tuning. ([~A3]). <u>_(Mentored by Alan Cooney, Google DeepMind)_</u>

\\[6px]

**Consultant**, _Office of the CTO, The Allen Institute, Seattle, WA_
  ~ **07/2025 - 09/2025**

- <u>Neural tracing</u>: Co-developed neural tracing for mechanistic interpretability of LLMs and bio-foundation models. Submitted patent application *"Model Optimization and Data Analysis Using Neural Traces"* ([~P2])

\\[50px]

**Research Scientist**, _Reality Labs Research, Meta_
  ~ **01/2022 - 04/2025**

- <u>Distributed Intelligence and On-device AI</u>: Prototyped gesture interaction for smart glasses (data collection, model training, compression, and demo) on SoC with custom and off-the-shelf accelerators. Through HW/SW codesign and energy-aware scheduling, my pipeline improved latency and power (by 93% \& 74%)
- <u>Performance and Power Modeling</u>: Built Python-based system-level power and performance modeling tool for Project Aria and other wearable devices using discrete-event simulation. The system latency and power was calibrated against measurements on prototype devices running machine perception pipelines: eye tracking, hand and gesture tracking, localization and mapping.
- <u>Hardware-Software-Security Codesign in Extended Reality</u>: Developed security and privacy research program for mixed and augmented reality, establishing threat models for codec avatars, privately crowdsourced data collection for world modeling, and other extended reality applications; published in HASP 2020 ([~W3]), PLDI 2021 ([~C5]), BMVC 2021 ([~C4]), TMLR 2025 ([~J4], [~A1])

\\[6px]

**Graduate Student Researcher**, _ArchLab, UC Santa Barbara_
  ~ **06/2015 - 12/2021**

- <u>Trace Wringing</u>: Developed trace wringing for safer program behavior sharing, achieving privacy through lossy compression and information flow tracking with verifiable leakage bounds; published in ASPLOS 2019, SEED 2021 ([~C3], [~C6]) and recognized as IEEE Micro Top Pick ([~J2])
- <u>Agile Hardware Development with PyRTL</u>: Co-developed PyRTL, a Pythonic hardware development toolkit enabling rapid prototyping and agile hardware design; published in FPL 2017 ([~C1]) and IEEE Micro 2020 ([~J3])
- <u>Architecture Modeling with Charm</u>: Worked on Charm, a domain-specific language for high-level architecture modeling; published in ISCA 2018, JETC 2019 ([~C2], [~J1])
- <u>OpenTPU</u>: Led development in PyRTL, creating open-source tensor processing unit implementation

\\[6px]

**Research Scientist Intern**, _Reality Labs Research, Meta_
  ~ **06/2020 - 01/2021**

- Implemented novel reverse engineering attack on local feature descriptors, surpassing state-of-the-art reconstruction accuracy for user image recovery
- Established first privacy threat model for computer vision feature descriptor sharing in AR systems
- Developed privacy-preserving mitigation techniques and studied effects on downstream vision system performance; published in BMVC 2021 ([~C4])

\\[6px]

**Research Intern**, _Microsoft Research_
  ~ **06/2018 - 09/2018**

- Implemented parameterizable architecture-aware machine learning graph primitives for custom hardware instructions on Brainwave Neural Processing Unit
- Built tools for automatic lifting of hardware instructions to high-level graph primitives while maintaining hardware fidelity
- Designed computational pipeline for NPU model decompilation with accuracy verification; resulted in patent ([~P1])

\\[6px]

**Research Assistant**, _Oracle Labs_
  ~ **06/2016 - 09/2016**

- Established testing environment for measuring throughput of RAPID Data Processing Unit (DPU) network, a bandwidth-optimized big data computation architecture
- Implemented network congestion tests for best/worst case traffic using hardware RPC acceleration mechanisms

## Publications

\\[6px]

_[C]=Conference, [J]=Journal or Magazine, [W]=Workshop_

\\[6px]

[~W4]: **The Need for Computational Pluralism** 

    <u>D. Dangwal</u>, A. Rajagopal.
    *Workshop on Ethical Systems and Architecture Design **(HotEthics)**, 2026*

\\[6px]

[~J4]: [**Unlocking Visual Secrets: Inverting Features with Diffusion Priors for Image Reconstruction**](https://arxiv.org/pdf/2412.10448)

    S. Q. Zhang, Z. Li, C. Guo, S. Mahloujifar, <u>D. Dangwal</u>, E. Suh, B. D. Salvo, C. Liu.
    *Transactions on Machine Learning Research **(TMLR)**, 2025*

\\[6px]

[~C6]: [**Context-Aware Privacy-Optimizing Address Tracing**](https://ieeexplore.ieee.org/document/9604789)

    <u>D. Dangwal</u>, Z. Zhang, J. Crandall, T. Sherwood.
    *IEEE International Symposium on Secure and Private Execution Environment Design **(SEED)**, 2021*

\\[6px]

[~C5]: [**Porcupine: A Synthesizing Compiler for Vectorized Homomorphic Encryption**](https://dl.acm.org/doi/10.1145/3453483.3454050)

    M. Cowan, <u>D. Dangwal</u>, A. Alaghi, C. Trippel, V. T. Lee, B. Reagen.
    *Programming Language Design and Implementation **(PLDI)**, 2021*

\\[6px]

[~C4]: [**Mitigating Reverse Engineering Attacks on Local Feature Descriptors**](https://bmva-archive.org.uk/bmvc/2021/assets/papers/1603.pdf)

    <u>D. Dangwal</u>, V. T. Lee, H. J. Kim, T. Shen, M. Cowan, R. Shah, C. Trippel, B. Reagen, T. Sherwood, V. Balntas, A. Alaghi, E. Ilg.
    *British Machine Vision Conference **(BMVC)**, 2021*

\\[6px]

[~W3]: [**SoK: Opportunities for Software-Hardware-Security Codesign for Next Generation Secure Computing**](https://arxiv.org/pdf/2105.00378) <span class="iconify" color="#43912B" data-icon="charm:trophy"></span>

    <u>D. Dangwal</u>, M. Cowan, A. Alaghi, V. Lee, B. Reagen, C. Trippel.
    *Hardware and Architectural Support for Security and Privacy **(HASP)**, 2020*

\\[6px]

[~J3]: [**Agile Hardware Development and Instrumentation with PyRTL**](https://ieeexplore.ieee.org/document/9099999)

    <u>D. Dangwal</u>, G. Tzimpragos, T. Sherwood.
    *IEEE Micro Special Topics on Agile & Open Source Hardware, 2020*

\\[6px]

[~J2]: [**Trace Wringing for Program Trace Privacy**](https://sites.cs.ucsb.edu/~sherwood/pubs/IEEEMicro-20-wringing.pdf) <span class="iconify" color="#43912B" data-icon="charm:trophy"></span>

    <u>D. Dangwal</u>, W. Cui, J. McMahan, T. Sherwood.
    *IEEE Micro's Top Picks from Computer Architecture Conferences, 2020 **(IEEE Micro Top Pick)***

\\[6px]

[~C3]: [**Safer Program Behavior Sharing through Trace Wringing**](https://dl.acm.org/doi/10.1145/3297858.3304074) <span class="iconify" color="#43912B" data-icon="charm:trophy"></span>

    <u>D. Dangwal</u>, W. Cui, J. McMahan, T. Sherwood.
    *Architectural Support for Programming Languages and Operating Systems **(ASPLOS)**, 2019*

\\[6px]

[~J1]: [**Language Support for Navigating Architecture Design in Closed Form**](https://dl.acm.org/doi/pdf/10.1145/3360047)

    W. Cui, G. Tzimpragos, Y. Tao, J. McMahan, <u>D. Dangwal</u>, N. Tsiskaridze, G. Michelogiannakis, D. Vasudevan, T. Sherwood.
    *ACM Journal on Emerging Technologies in Computing Systems **(JETC)**, 2019*

\\[6px]

[~W2]: [**PyRTLMatrix: an Object-Oriented Hardware Design Pattern for Prototyping ML Accelerators**](https://sites.cs.ucsb.edu/~sherwood/pubs/EMC2-19-pyrtl-matrix.pdf)

    D. Aboye, D. Kupsh, M. Lim, J. Mai, <u>D. Dangwal</u>, D. Mirza, T. Sherwood.
    *Workshop on Energy Efficient Machine Learning and Cognitive Computing for Embedded Applications **(EMC2)**, 2019*

\\[6px]

[~W1]: [**PyRTL in Early Undergraduate Research**](https://dl.acm.org/doi/10.1145/3338698.3338890)

    D. Mirza, <u>D. Dangwal</u>, T. Sherwood.
    *Workshop on Computer Architecture Education **(WCAE)**, 2019*

\\[6px]

[~C2]: [**Charm: A Language for Closed-form High-level Architecture Modeling**](https://ieeexplore.ieee.org/document/8416825)

    W. Cui, Y. Ding, <u>D. Dangwal</u>, A. Holmes, J. McMahan, A. JavadiAbhari, G. Tzimpragos, F. Chong, T. Sherwood.
    *International Symposium on Computer Architecture **(ISCA)**, 2018*

\\[6px]

[~C1]: [**A Pythonic Approach for Rapid Hardware Prototyping and Instrumentation**](https://ieeexplore.ieee.org/document/8056860)

    J. Clow, G. Tzimpragos, <u>D. Dangwal</u>, S. Guo, J. McMahan, T. Sherwood.
    *International Conference on Field-Programmable Logic and Applications **(FPL)**, 2017*

## Pre-Prints, Reports, Articles

[~A3]: **Position: Safety Monitoring Should Operate on Weights During Fine-Tuning**

    <u>D. Dangwal</u> et al.
    *In preparation, 2026*

\\[6px]

[~A2]: [**Mechanism Design for Improving Hardware Security Workshop Report**](https://cra.org/ccc/wp-content/uploads/sites/2/2023/04/01378-Mechanism-Design-Workshop-Report.pdf)
    *CCC Workshop Report, August 2022*

\\[6px]

[~A1]: [**Analysis and Mitigations of Reverse Engineering Attacks on Local Feature Descriptors**](https://arxiv.org/abs/2105.03812)

    <u>D. Dangwal</u>, V. T. Lee, H. J. Kim, T. Shen, M. Cowan, R. Shah, C. Trippel, B. Reagen, T. Sherwood, V. Balntas, A. Alaghi, E. Ilg.
    *arXiv preprint, May 2021*

## Patents

[~P2]: **Model Optimization and Data Analysis Using Neural Traces**

    A. Rajagopal, G. H. Huynh, <u>D. Dangwal</u>
    *Provisional Patent Filed September 2025*

\\[6px]

[~P1]: [**Deriving a concordant software neural network layer from a quantized firmware neural network layer**](https://patents.google.com/patent/US11556764B2/en)

    J. Fowers, D. Lo, <u>D. Dangwal</u>
    *US Patent 11556764B2, Microsoft Technology Licensing LLC, 2023*

\\[30px]

## Invited Talks and Seminars

[~T8]: **Performance, Power, and Privacy: Codesign Strategies for Always-On Wearables**

    Washington State University, Pullman
    ~ 06/2025

\\[6px]

[~T7]: **Privacy and Security in the age of Metaverse: A case for data minimization and on-device AI**

    Washington State University, Everett
    ~ 05/2025

\\[6px]

[~T6]: **A System-Level Framework for Privacy: Applications of Wringing in AR/VR**

    Meta, Reality Labs Research
    ~ 03/2021

\\[6px]

[~T5]: **A System-Level Framework for Privacy**

    Arizona State University, Phoenix
    ~ 03/2021

\\[6px]

[~T4]: **A System-Level Framework for Privacy**

    Pennsylvania State University, State College
    ~ 03/2021

\\[6px]

[~T3]: **Privacy through Wringing**

    UCSB Grad Slam Final
    ~ 03/2021

\\[6px]

[~T2]: **Agile hardware development and instrumentation with PyRTL**

    Agile-RTL Workshop, UC Santa Barbara, CA
    ~ 09/2019

\\[6px]

[~T1]: **OpenTPU: Prototyping ML Accelerators with PyRTL**

    IEEE Space Computing Conference, Caltech, Pasadena, CA
    ~ 09/2019

## Teaching and Mentorship

**Mentor**, SPAR (Supervised Program for Alignment Research)
  ~ **Fall 2026**

- Project: [*Constraint Drift Through Delegation Hierarchies*](https://sparai.org/projects/f26/recIHq2myqMGSkiHs/), co-mentored with Abhejit Rajagopal (Allen Institute, UCSF)

\\[6px]

**Teaching Assistant**, CS 154: Computer Architecture, UCSB
  ~ Spring 2021

\\[6px]

**Teaching Assistant**, Research Mentorship Program (RMP), UCSB
  ~ Summer 2019

\\[6px]

**NSF ERSP Mentor**, Department of Computer Science, UCSB
  ~ 2018 - 2019

- Students published "PyRTLMatrix: an Object-Oriented Hardware Design Pattern for Prototyping ML Accelerators" at EMC2 workshop ([~W2])
- Awarded university-wide Fiona and Michael Goodchild Graduate Mentoring Award <span class="iconify" color="#43912B" data-icon="charm:trophy"></span>

  for excellence in mentorship

\\[6px]

**Women in STEM Mentorship Program**, UCSB
  ~ 10/2016 - 03/2018

\\[6px]

**Teaching Assistant**, Department of Physics, UCSB
  ~ 01/2015 - 06/2015

\\[6px]

**EUREKA Mentorship Program**, California NanoSystems Institute, UCSB
  ~ 06/2015 - 08/2015

\\[6px]

**Students Mentored**
  * Joann Chen (Research Intern, Meta, 2022), Manu Kondapaneni (2020), Junayed Naushad (2019), Dawit Aboye (2018-2019), Dylan Kupsh (2018-2019), Maggi Lim (2018-2019), Jacqueline Mai (2018-2019), Angela Yung (2016-2017), Saurabh Gupta (2015)

## Professional Service and Activities

**CRA Congressional Visit Day**, Washington State Contingent
  ~ 09/2025

- Represented CRA and Washington State in Washington, D.C., and joined meetings with

  Members of Congress to make the case for federal support of computing research

\\[6px]

**Invited Participant, CCC Future of AI Research in Industry**
  ~ 07/2025

\\[6px]

**Invited Participant, CCC Computing Futures Symposium**
  ~ 05/2025

\\[6px]

**Invited Participant, CCC Mechanism Design for Improving Hardware Security**
  ~ 08/2022

\\[6px]

**Organizer**, Undergrad Architecture Mentoring Workshop (uArch)
  ~ 2022 - 2025

\\[6px]

**Program Committee Member**
  * MICRO '26, ISPASS '26, HPCA ('26, '25, '24), ASPLOS '25, ISCA '24, SEED '24, HASP '23

\\[6px]

**External Review Committee**
  * MICRO '24, YArch ('25, '23), ISCA '22, SEED '21, ASPLOS '20 (Artifact Evaluation)

\\[6px]

**Co-President, Women in Computer Science (WiCS), UCSB**
  ~ 2018 - 2020

\\[6px]

**Graduate Representative for Faculty Recruitment**, Department of Computer Science, UCSB
  ~ 2019 - 2020

\\[6px]

**Graduate Representative for Diversity**, Department of Computer Science, UCSB
  ~ 2018 - 2019

\\[6px]

**Grace Hopper Celebration of Women**
  ~ 2017, 2018, 2019

\\[6px]

**CRA-W Grad Cohort**
  ~ 2017, 2018

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>_(Updated October 2026)_