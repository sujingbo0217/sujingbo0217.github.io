---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

## Education

* **University of California, Riverside**
  * Graduate Preparation Program in Engineering, 2023 - 2024
  * GPA: 3.76/4.0

* **North China University of Technology**
  * Mechanical Engineering, 2020 - 2021
  * Bachelor's Degree in Computer Science, 2021 - 2024
  * GPA: 3.81/4.0

## Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- ## Research Presentations

* The 18th International Conference on Intelligent Information Hiding and Multimedia Signal Processing, 2022 (IIHMSP'22). -->

## Research Experience

* **UC, Riverside Parallel Algorithm Lab** with Prof. Yan Gu and Prof. Yihan Sun
* Project: [*ANNlib: Quickly Build-up Your Approximate Nearest Neighbor System*](https://github.com/ucrparlay/ANNlib)
  * Reproduced existing graph-based filtered ANNS algorithms on ANNlib system by using interfaces provided by ANNlib to demonstrate the ability of ANNlib system to support various graph-based ANNS algorithms
  * Refactored experimental code, encapsulated each ANNS algorithm into modules for easier evaluating. Developers can implement their own graph-based ANNS algorithms with a separate codebase, which reflects the engineering and user-friendliness of ANNlib system
  * Designed ablation experiments and evaluated multiple ANNS algorithms on various vector dataset benchmarks. Recorded and analyzed the index construction delay, search accuracy (recall) and throughput (QPS) as the performance of graph-based ANNS algorithms
  * Experimental results showed that these algorithms can perform as efficiently or better on ANNlib system than their well-optimized counterparts

* **NCUT Evolutionary Computing Lab** with Prof. Ruobin Wang and Dr. Lin Xu
* Project: [*A Parallel Gannet Optimization Algorithm with Communication Strategies (PGOA)*](https://github.com/sujingbo0217/PGOA)
  * Presented final research findings at the 18th International Conference on Intelligent Information Hiding and Multimedia Signal Processing, substantially enhancing my communication skills and academic English proficiency
  * Carried out experiments with CEC-2013 to benchmark against the baseline Gannet Optimization Algorithm
  * Evaluated on both compact and parallel techniques. Experiential results demonstrated that the parallel strategy significantly surpassed the original GOA algorithm in computational efficiency and precision
  * Contributed to weekly lab meetings by conducting literature reviews on 10+ papers about Evolutionary Computing and presenting emerging concepts at graduate-level group discussions
  
## Work Experience

* **China National Investment & Guaranty Corporation**
* Full-Stack Software Developer Intern
  * Applied full-stack development techniques by leveraging various frameworks (Django, React, SpringBoot) and refining programming skills in multiple languages (Python, TypeScript, Java)
  * Developed a project management system, using Django for backend and React for frontend, that significantly optimized project management processes and enhanced product managers' efficiency
  * Independently built a script manager tool that empowered 20+ engineers to manage and execute Python scripts, contributing to streamlined script management and enhanced productivity across the team

## Selected Projects

* **UC, Riverside CS222 - Natural Language Processing**
* Project: [*Enhancing Adversarial Attacks through Chain of Thought*](https://github.com/sujingbo0217/CS222W24-LLM-Attack)
  * Explored a novel attack method to raise success rates of adversarial attacks on large language models (LLMs)
  * Integrated chain-of-thought (CoT) prompting into a gradient-based adversarial attack on aligned LLMs and conducted experiments comparing performance on both baseline and Amazon's auto-cot
  * Evaluated the ablation studies on various harmful types categorized by *Llama-Guard*, demonstrating that the novel method successfully triggered the CoT ability on multiple aligned LLMs during attacks and outperformed prior approaches.

* **UC, Riverside CS178 - Project Sequence**
* Project: [*MedShare: Healthcare Made Easy*](https://github.com/UCR-Senior-Design/course-project-fries)
  * Built an easily-use medical management system with key features like messaging, forums, and appointment scheduling, integrating an API-callable chatbot to effectively enhance communication between doctors and patients and reduce healthcare delays.
  * Designed and implemented the frontend and backend of the system using ReactJS, NodeJS, and MongoDB. Employed GitHub to do version control for the project. Ensured efficient data management and a user-friendly interface.
  * Designing a chatbot system based on the LangChain framework and deploying it in a distributed manner with the Node system. Utilizing the Retrieval Augmented Generation (RAG) technique enables doctors to upload patient-related documents to flesh out the system knowledge base.

<!-- * **Efficient large language model fine-tuning via multiple LoRA adapters**
  * Implemented a dispatcher to load multiple input data and batch them respectively, allowing for aligned combinations of the batched data.
  * Adjusted various structures of decoder-only large language models. The Meta Open Pre-trained Transformer language model was supported during tests.
  * Evaluated the multi-LoRA fine-tune system against the normal one (single LoRA adapter fine-tune system), confirming that our system can efficiently utilize computational resources, thereby increasing the fine-tune system throughput. -->

<!-- * **NES (Nintendo Entertainment System)**
  * Implemented a simulation of the 6502 CPU, RAM, and MainBus, including the processes of instruction fetching, decoding, and execution. Successful enabled data Read and Write operations within the CPU.
  * Utilized the ca65 compiler and ld65 linker to compile the assembly code. Analyzed the resulting binary file to test the functionality of the code.
  * Developed an emulator that seamlessly integrated diverse components. Employed the SFML library for game display, incorporated the Picture Bus and Virtual Screen functionalities, and integrated controller mechanisms to capture users' keyboard inputs. -->

<!-- * **Operating System Practice - Dec. 2022**
  * [GitHub Repo Here](https://github.com/NCUT-lambda/our-xv6-riscv)
  * [Get Chinese Guidebook Here](https://ncut-lambda.github.io/our-xv6-riscv/)
  * Engaged in extensive study of relevant manuals, delving deeply into the foundational principles of the system call and its implementation within the xv6-riscv source code.
  * Contributed valuable insights by adding comments to critical sections within the scope of system call in the xv6-riscv source code. These annotations not only captured my thought process but also enhanced team's comprehension and fostered collaborative efforts.
  * Executed the system call code scope, incorporating gnu-gdb breakpoints for precise debugging. Ensured a thoroughly understanding of the implementation and functionality of the scope of system call.
  * Participated in thought-provoking discussions with both fellow team members and the professor, exploring and analyzing the design patterns inherent within the xv6-riscv operating system. This collaborative exchange of ideas significantly enriched the collective comprehension of the architecture.
  * Collaboratively created a comprehensive guidebook with my teammates, encapsulating our collective insights and discoveries. Perfectly delivered a presentation of our insights and discoveries in front of the class.

* **Deep Learning Specialization - Jul. 2023**
  * [Get My Note Here](https://sujingbo0217.github.io/posts/2023/08/blog-post-1/)
  * Explored neural network fundamentals, including vectorization, forward and backward propagation, and gradient descent. Implemented shallow and deep neural networks to translate theory into practice.
  * Mastered advanced techniques for network regularization, involving L1, L2, and Frobenius norm, as well as the innovative dropout method. Investigated optimization algorithms, with special focus on the Exponentially Weighted Averages technique for enhancing neural network training efficiency. Gained a comprehensive grasp of the Adam optimization algorithm. Delved into the batch normalization, its advantageous role in both expediting learning and subtly regularizing networks within training mini-batches and testing sets. -->

## Awards

* 2021 & 2022 NCUT Scholarship - CNY 2,000
* 2022 NCUT CS Competition Awards - CNY 2,000
* 2021 Silver medal in the 15th Programming Competition of NCUT
* Honorable Mention in the 46th ICPC Asia Regional Programming Contest

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
