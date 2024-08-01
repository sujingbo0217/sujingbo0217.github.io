---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

## Education

* **North China University of Technology**
  * Mechanical Engineering, Sep. 2020 - Jul. 2021
  * Bachelor's Degree in Computer Science, Sep. 2021 - Jul. 2024
  * GPA: 3.81/4.0

* **University of California, Riverside**
  * Graduate Preparation Program in Engineering, Sep. 2023 - Jul. 2024
  * GPA: 3.76/4.0

## Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- ## Research Presentations

* The 18th International Conference on Intelligent Information Hiding and Multimedia Signal Processing, 2022 (IIHMSP'22). -->

## Research Experience

* **UC, Riverside Parallel Algorithm Lab** with Prof. Yihan Sun and Prof. Yan Gu
  * Designed a powerful parallel computing library, which supports plug-and-play graph-based ANNS modules, including graph-based vector indices, ANNS algorithms, and filtered indices, etc. The objective is to simplify the system design process and and provide an efficient means for developers to test and evaluate the performance of their graph-based ANNS algorithms.
  * Integrated the existing filtered ANNS algorithms into the framework as one of the applications. Evaluated the integrated filtered ANNS algorithms on various filtered vector datasets. The results demonstrated that both the throughput (QPS) and the accuracy (recall) are superior to those achieved by the same algorithm on its original framework and many SOTA vector databases.

* **UC, Riverside CS222 Final Project**
  * Combined gradient-based adversarial attack techniques with Chain of Thought (CoT) prompting to study a universal and transferable adversarial CoT suffix to trigger the CoT ability of various large language models (LLMs).
  * Implemented and evaluated attack approach based on existing codebase -- *llm-attacks*, ran experiments comparing performance to both baseline methods and Amazon's *auto-cot*, and evaluated the generated content on *Llama-Guard*.
  * Evaluated the ablation studies on various harmful types categorized by *Llama-Guard*, demonstrating that the novel method successfully triggered the CoT ability on multiple aligned LLMs during attacks and outperformed prior approaches.

* **NCUT Evolutionary Computing Lab** with Prof. Ruobin Wang and Dr. Lin Xu
  * Conducted literature reviews in Evolutionary Computing and actively participated in group learning and discussions on emerging concepts through group meetings with graduate students.
  * Carried out experiments using various methods such as compact and parallel to benchmark against the baseline Gannet Optimization Algorithm, and demonstrated that the parallel strategy significantly surpassed the original in both computational efficiency and precision.
  * Presented camera-ready slides at the 18th International Conference on Intelligent Information Hiding and Multimedia Signal Processing, substantially enhancing my communication skills and academic English proficiency.
  
## Industry Experience

* **Software Developer Intern in China National Investment \& Guaranty Corporation**
  * Refined Python, Java, and TypeScript programming languages, with proficiency in utilizing development frameworks such as Django, SpringBoot, and React. Acquired a comprehensive grasp of full-stack development techniques, encompassing both backend and frontend principles.
  * Developed a project management system. Employed Django as the robust backend framework and implemented the frontend using React with a multitude of components. This system significantly optimized project management processes and enhanced product managers efficiency.
  * Crafted a range of utility tools, among which a Python script-manager independently created using Python Tkinter stands out. This tool empowered colleagues to seamlessly manage, display, and execute their Python scripts, contributing to streamlined script management and enhanced productivity across the team.

## Project Experience

* **CS178 Senior Design - MedShare** with Prof. Mariam Salloum
  * Built an easily-use medical management system with key features like messaging, forums, and appointment scheduling, integrating an API-callable chatbot to effectively enhance communication between doctors and patients and reduce healthcare delays.
  * Designed and implemented the frontend and backend of the system using ReactJS, NodeJS, and MongoDB. Employed GitHub to do version control for the project. Ensured efficient data management and a user-friendly interface.
  * Designing a chatbot system based on the LangChain framework and deploying it in a distributed manner with the Node system. Utilizing the Retrieval Augmented Generation (RAG) technique enables doctors to upload patient-related documents to flesh out the system knowledge base.

* **Efficient large language model fine-tuning via multiple LoRA adapters**
  * Implemented a dispatcher to load multiple input data and batch them respectively, allowing for aligned combinations of the batched data.
  * Adjusted various structures of decoder-only large language models. The Meta Open Pre-trained Transformer language model was supported during tests.
  * Evaluated the multi-LoRA fine-tune system against the normal one (single LoRA adapter fine-tune system), confirming that our system can efficiently utilize computational resources, thereby increasing the fine-tune system throughput.

* **NES (Nintendo Entertainment System)**
  <!-- * [GitHub Repo Here](https://github.com/sujingbo0217/NES) -->
  * Implemented a simulation of the 6502 CPU, RAM, and MainBus, including the processes of instruction fetching, decoding, and execution. Successful enabled data Read and Write operations within the CPU.
  * Utilized the ca65 compiler and ld65 linker to compile the assembly code. Analyzed the resulting binary file to test the functionality of the code.
  * Developed an emulator that seamlessly integrated diverse components. Employed the SFML library for game display, incorporated the Picture Bus and Virtual Screen functionalities, and integrated controller mechanisms to capture users' keyboard inputs.

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
