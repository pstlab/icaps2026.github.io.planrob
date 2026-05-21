---
title: "ICAPS'26 Workshop: PlanRob"
date: 2025-04-29T00:00:00+00:00
draft: false
---

# 14<sup>th</sup> Workshop on Planning and Robotics (PlanRob)

Co-located workshop at ICAPS'26  \
Dublin, Ireland \
June 29, 2026

Paper submission deadline extended to 2nd of May, 2026.

## Aim and Scope of the Workshop

AI Planning & Scheduling (P&S) methods are crucial to enabling intelligent robots to perform autonomous, flexible, and interactive behaviors, but they must be tightly integrated into the overall robot architecture in order to be effective. This requires strong collaboration between researchers from both the AI and the Robotics communities. To foster this, the workshop aims to provide a stable, long-term forum where researchers from both the P&S and Robotics communities can openly discuss relevant issues such as research and development progress, future directions, and open challenges related to P&S when applied to Robotics. Recent advances in large-scale learning models, multimodal perception, and whole-body robotic systems are reshaping the landscape of planning and execution. The 2026 edition of PlanRob explicitly aims to address these emerging challenges, with a focus on integrating symbolic, geometric, and learning-based approaches for robust, scalable, and adaptive robot autonomy.



## Topics of Interest

Topics of interest include but are not limited to:

* Planning representations and models for robotics including domain modeling, abstraction, and formal representations
* Robot planning at multiple levels, including mission, task, path, motion, and integrated task-and-motion planning
* Learning-augmented planning for robotics, including:
    - learning-based methods for planning and control
    - generative models for planning    
    - continual learning and planning architectures and algorithms
* Foundation-model-based approaches for robot planning, including: 
    - LLM-, VLM-, and action-model-based methods for task as well as task-and-motion planning
    - perception-grounded planning using vision-language representations
* Planning, execution, and control integration, including robot architectures supporting tight coupling between deliberation and execution
* Planning for complex robotic systems, including: 
    - high-dimensional and whole-body robotic planning and execution
    - planning under real-world sensing
    - actuation, and computational constraints
* Multi-agent and interactive planning, including: 
    - coordination and cooperation in multi-robot systems
    - human-aware planning and execution for human–robot interaction
    - adversarial and competitive planning in robotic domains
* Formal and algorithmic foundations of robot planning, including formal methods for verification, correctness, and safety
* Large-scale and real-world robotic applications, including: 
    - optimization of behavior in large-scale automated or semi-automated systems
    - deployment and evaluation of planning methods on autonomous and intelligent robots in real-world settings

Important goals of the workshop are the discussion of solutions, results, open issues, and real-world challenges.


## Important Dates

- *Extended Submission Deadline*: May 2, 2026 (AoE) (was April 20, 2026)
- *Extedend Author Notification*: May 30, 2026 (was May 5, 2026)
- Camera-Ready Deadline: June 5, 2026
- ICAPS 2026 Workshops: June 28-29, 2026

Note that at the date of the submission deadline, all papers need to be registered, which includes all relevant information such as title, abstract, authors, and kind of paper (long, short, ...). 

## Invited Talk by [NICK HAWES](https://eng.ox.ac.uk/people/nick-hawes)
![Nick](nick-hawes-happy.jpeg)

<img src="nick-hawes-happy.jpeg" alt="Alt Text" width="300">

Title: Long-Range Underwater Glider Planning Under Uncertainty

Abstract: Underwater gliders are workhorses of ocean sampling. They’re slow but energy-efficient, capable of operating for many months at sea. However, they're notoriously hard to pilot: glider dynamics are uncertain and strongly influenced by ocean currents (which are also hard to forecast), and glilders are only in contact with operators during brief surfacing windows between dives. Therefore the long-term autonomous operation of gliders fleets has remained largely aspirational, with most missions still leaning heavily on human pilots. In this talk I'll present GALE, the Glider Autonomy Long-term Planning Engine, which treats glider piloting as a stochastic shortest-path MDP and solves it online with Monte Carlo Tree Search (MCTS). The MCTS samples are drawn from a physics-informed simulator whose parameters are fitted to historical glider data, capturing both control-execution noise and ocean-current forecast uncertainty while staying cheap enough to roll out at every surfacing. I'll describe how the system was deployed in two North Sea missions totalling around three months and 1000 km of fully autonomous operation (to date the most extensive deployment of online glider navigation planning) and what we learned about where model-based probabilistic planning outperforms simpler baselines.
 
Bio-sketch: Nick Hawes is a Professor of AI and Robotics in the [Department of Engineering Science](https://eng.ox.ac.uk/) at the [University of Oxford]([url](https://www.ox.ac.uk/)), where he directs the [Oxford Robotics Institute (ORI)](https://ori.ox.ac.uk/), a federation of eight research groups. He is also a Tutorial Fellow at [Pembroke College](https://pmb.ox.ac.uk/). Within ORI, he leads the [Goal-Oriented Autonomous Long-Lived Systems (GOALS)](https://ori.ox.ac.uk/groups/goals) group, researching sequential decision-making for autonomous systems and multi-agent teams. He has led world-first deployments of AI-controlled robots, including long-term autonomous mobile robots in care and security, quadrupeds inspecting active nuclear sites, and AUVs gathering data on underwater ecosystems. He is a member of the [UK Government's Robotics Advisory Group](https://www.gov.uk/government/groups/robotics-advisory-group), an Associate Editor of the [Journal of AI Research](https://www.jair.org/), a Senior Member of [AAAI](https://aaai.org/), and Chief Scientist of [Stateful Robotics](https://statefulrobotics.com/).

## Submission Instructions

There are two types of submissions: 
- short position papers (four pages)
- regular papers (up to 10 pages)

Papers may have an additional page containing references. Regular papers may be scheduled with more time in the final program. A poster session may be considered to provide a further presentation opportunity.

The guidelines for formatting are the same as is used for ICAPS 2026 papers as described at: [http://www.aaai.org/Publications/Author/author.php](http://www.aaai.org/Publications/Author/author.php)), but with the AAAI copyright removed. The papers must be submitted in PDF format via the EasyChair system ([https://easychair.org/conferences/?conf=planrob26](https://easychair.org/conferences/?conf=planrob26)).

Please note that papers under review (e.g. which have been submitted to IJCAI-2026) are also welcome, however, in order to avoid potential conflicts, these manuscripts should be prepared as anonymous submissions for a double blind reviewing process.


### Workshop Proceedings

Accepted papers will be published on the workshop's website.

The organisers are investigating the availability of journal editors in order to invite a selection of accepted papers from the workshop to a special issue or post-proceedings volume.


## Program Committee

- Zlatan Ajanovic (RWTH Aachen University, Germany)
- Iman Awaad (Hochschule Bonn-Rhein-Sieg, Germany)
- Roman Barták (Charles University, Czech Republic)
- Arthur Bit-Monnot (LAAS-CNRS, France)
- Ronen Brafman (Ben-Gurion University, Israel)
- Jonathan Cacace (EURECAT, Spain)
- Riccardo Caccavale (Naples University, Italy)
- Michael Cashmore (University of Strathclyde, UK)
- Riccardo De Benedictis  (CNR-ISTC, Italy)
- Alberto Finzi (Naples University, Italy)
- Nick Hawes (University of Oxford, UK)
- Felix Ingrand (LAAS-CNRS, France)
- Luca Iocchi (Sapienza University, Italy)
- Matteo Iovino (ABB, Sweden)
- Erez Karpas (Technion, Israel)
- Matteo Leonetti (King’s College, UK)
- Oscar Lima (DFKI, Germany)
- Masoumeh Mansouri  (University of Birmingham, UK)
- Tim Niemuller (Intrinsic, Germany)
- Andrea Orlandini (CNR-ISTC, Italy)
- Ron Petrick (Heriot-Watt University, UK)
- Angel Santamaria Navarro (UPC, Spain)
- Enrico Scala (UniBS, Italy)
- Mohan Sridharan (University of Birmingham, UK)
- Sebastian Stock (DFKI, Germany)
- Elisa Tosello (FBK, Italy)
- Magí Dalmau Moreno, Universitat Pompeu Fabra
- Jane Jean Kiam, Universität der Bundeswehr München
- Senka Krivic, University of Sarajevo
- Pulkit Verma, Massachusetts Institute of Technology
- Alessandro Umbrico (CNR-ISTC, Italy)

Please reach out to the organisers if you are interested in joining the program committee in future.

## Organizing Committee

[Iman Awaad](https://www.h-brs.de/en/inf/iman-awaad), [iman.awaad@h-brs.de](mailto:iman.awaad@h-brs.de)  
Institute for AI & Autonomous Systems, Hochschule Bonn-Rhein-Sieg, Germany  
& German International University, Egypt 

[Alberto Finzi](http://wpage.unina.it/alberto.finzi/), [alberto.finzi@unina.it](mailto:alberto.finzi@unina.it)  
Università di Napoli “Federico II”, Italy 

[Andrea Orlandini](https://www.istc.cnr.it/people/andrea-orlandini), [andrea.orlandini@istc.cnr.it](mailto:andrea.orlandini@istc.cnr.it])  
Institute of Cognitive Sciences and Technologies (ISTC-CNR), Italy


## Organizing Committee

This workshop is partially supported by TRIFFID whose aim is to revolutionize the landscape of emergency response by seamlessly weaving advanced robotics with the crucial work of First Responders, ensuring they’re equipped to tackle disasters with unparalleled efficiency and precision. Innovative hybrid robotic platforms aims at blend autonomous legged and aerial capabilities, enabling real-time reconnaissance even in the most challenging terrains, while our sophisticated Ground-Station interface empowers operators to visualize and analyze disaster scenarios like never before. TRIFFID has received funding from the European Union’s Horizon Europe research and innovation programme under grant agreement No.101168042.
