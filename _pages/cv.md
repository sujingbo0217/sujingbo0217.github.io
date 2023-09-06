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

* Mechanical Engineering, North China University of Technology, Sep. 2020 - Jul. 2021
* Computer Science and Technology, North China University of Technology, Sep. 2021 - Jul. 2023
* Graduate Preparation Program in Engineering, University of California - Riverside, Sep. 2023 - Present
* GPA: 3.82/4.0

## Publications

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Research Presentations

* The 18th International Conference on Intelligent Information Hiding and Multimedia Signal Processing, 2022 (IIHMSP'22).

## Research Experience

* Evolutionary Computing, Research Assistant, North China University of Technology, Sep. 2022
  * Conducted an in-depth literature review, meticulously analyzing relevant papers to attain a comprehensive understanding of the core principles underlying the Evolutionary Computing.
  * Organized and participated in regular group meetings, facilitating collaborative learning and engaging in discussions about emerging concepts with fellow graduate students.
  * Independently conducted a series of experiments encompassing a host of methods and algorithms, specifically targeting the benchmarking against the original Gannet Optimization Algorithm.
  * Analyzed the experiment results and attained exceptional outcomes that the parallel method outperformed in terms of both computational efficiency and precision when compared to the original Gannet Optimization Algorithm.
  * Spearheaded the creation of camera-ready materials and engaged the oral presentation on the international conference, a great opportunity to improve my academic expression and English skills.

* Underwater Object Detection, Research Assistant, University of South Australia (Online), Jan. 2023
  * Created a custom squid-fish dataset by sourcing images from online sources. Employed precise annotation and labeling techniques to ensure the dataset's accuracy and relevance.
  * Directed the training and prediction phases using the YOLO (You Only Look Once) model, adeptly fine-tuning it to accommodate the custom underwater fish dataset.
  * Integrated the Class Activation Mapping (CAM) tool into the YOLO model, enabling the examination of attention patterns within the output layers. Collaboratively supported the research team by fortifying their efforts with an enhanced YOLO model.
  
## Industry Experience

* Software Developer Intern, China National Investment \& Guaranty Corporation, Mar. 2023 - Jul. 2023
  * Advanced in Python, Java, and TypeScript programming languages, with proficiency in utilizing development frameworks such as Django, SpringBoot, and React. Acquired a comprehensive grasp of full-stack development techniques, encompassing both backend and frontend principles.
  * Individually designed and developed a project management system. Employed Django as the robust backend framework and implemented the frontend using React with a multitude of components. This system significantly optimized project management processes and enhanced product managers efficiency.
  * Innovatively crafted a range of utility tools, among which a Python script-manager independently created using Python Tkinter stands out. This tool empowered colleagues to seamlessly manage, display, and execute their Python scripts, contributing to streamlined script management and enhanced productivity across the team.

## Project Experience

* NES (Nintendo Entertainment System) - May, 2022
  * [GitHub Repo Here](https://github.com/sujingbo0217/NES)
  * Implemented a simulation of the 6502 CPU, RAM, and MainBus, including the processes of instruction fetching, decoding, and execution. Successful enabled data Read and Write operations within the CPU.
  * Utilized the ca65 compiler and ld65 linker to compile the assembly code. Analyzed the resulting binary file to test the functionality of the code.
  * Developed an emulator that seamlessly integrated diverse components. Employed the SFML library for game display, incorporated the Picture Bus and Virtual Screen functionalities, and integrated controller mechanisms to capture users' keyboard inputs.
* Operating System Practice - Dec. 2022
  * [GitHub Repo Here](https://github.com/NCUT-lambda/our-xv6-riscv)
  * [Get Chinese Guidebook Here](https://ncut-lambda.github.io/our-xv6-riscv/)
  * Engaged in extensive study of relevant manuals, delving deeply into the foundational principles of the system call and its implementation within the xv6-riscv source code.
  * Contributed valuable insights by adding comments to critical sections within the scope of system call in the xv6-riscv source code. These annotations not only captured my thought process but also enhanced team's comprehension and fostered collaborative efforts.
  * Executed the system call code scope, incorporating gnu-gdb breakpoints for precise debugging. Ensured a thoroughly understanding of the implementation and functionality of the scope of system call.
  * Participated in thought-provoking discussions with both fellow team members and the professor, exploring and analyzing the design patterns inherent within the xv6-riscv operating system. This collaborative exchange of ideas significantly enriched the collective comprehension of the architecture.
  * Collaboratively created a comprehensive guidebook with my teammates, encapsulating our collective insights and discoveries. Perfectly delivered a presentation of our insights and discoveries in front of the class.
* Deep Learning Specialization - Jul. 2023
  * [Get My Note Here](https://sujingbo0217.github.io/posts/2023/08/blog-post-1/)
  * Explored neural network fundamentals, including vectorization, forward and backward propagation, and gradient descent. Implemented shallow and deep neural networks to translate theory into practice.
  * Mastered advanced techniques for network regularization, involving L1, L2, and Frobenius norm, as well as the innovative dropout method. Investigated optimization algorithms, with special focus on the Exponentially Weighted Averages technique for enhancing neural network training efficiency. Gained a comprehensive grasp of the Adam optimization algorithm. Delved into the batch normalization, its advantageous role in both expediting learning and subtly regularizing networks within training mini-batches and testing sets.

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
