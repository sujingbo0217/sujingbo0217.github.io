---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
---

Greetings! I am Jingbo (Bob) Su, graduated from Computer Science and Technology at [North China University of Technology](http://www.ncut.edu.cn), Beijing, China. At present, I am working as a research assistant at [UC Riverside Parallel Algorithm Lab](https://pal.cs.ucr.edu) advised by Professor [Yan Gu](https://www.cs.ucr.edu/~ygu) and [Yihan Sun](https://www.cs.ucr.edu/~yihans). I previously worked with Professor Ruobin Wang and Dr. Lin Xu in the Evolutionary Algorithm Lab at NCUT. During my final year of undergraduate, I enrolled in the [Graduate Preparation Programs](https://gpp.ucr.edu/) and earned an Advanced Certificate in Engineering.

My research interests are ***parallel algorithms***, ***approximate nearest neighbor search***, ***vector databases***, and ***affective computing***.

## On-going Projects

### Efficient Parallel Graph-based Approximate Nearest Neighbor Library (ANNlib)

**ANNlib** is the project I am doing now at UCR PAL. **ANNlib** is an efficient system that supports developers in designing, building and evaluating their own graph-based ANNS algorithms. We modularly encapsulate a host of public components commonly used by various prevlant graph-based ANNS algorithms such as [DiskANN](https://papers.nips.cc/paper_files/paper/2019/file/09853c7fb1d3f8ee67a61b6bf4a7f8e6-Paper.pdf), [HNSW](https://arxiv.org/pdf/1603.09320), [HCNNG](https://www.sciencedirect.com/science/article/abs/pii/S0031320319302730), etc. By evaluating several of the above and other graph-based ANN algorithms on our system and comparing the results with the performance of these algorithms on their original systems, we find that our system performs better, or at least as well, in terms of accuracy (recall) and throughput (QPS). In essence, our system enables ANN researchers and developers to easily design and evaluate their own graph-based ANN algorithms in the same environment, and to implement more sophisticated operations such as dynamic insertion-deletion and hybrid filtered search.

## Skills

* Languages
  * English (Fluent), Mandarin Chinese (Native)
* Programming
  * C/C++(20), Python, JavaScript/TypeScript, MySQL, $\LaTeX$
* Frameworks/Libraries
  * ANNlib, ParlayLib, PyTorch, LangChain, React, Django

## Hobbies

* Fencing
  * Eighth place in the national middle school team competition (2014)
  * Champion in the provincial middle school individual competition (2015)
* Swimming
  * 50M freestyle - 35s (2024)
* Running (Sprint)
  * 50M - 6.4s (2021)
  * 100M - 12.5s (2018)
* Soccer
  * Member of high school soccer club (2018-2019)
* [Photography](https://sujingbo0217.github.io/photography)

<!-- Currently, I am conducting research on graph-based approximate nearest neighbor algorithms at UCR PAL with. Existing ANNS algorithms do not have an efficient way to perform filtered search, especially on high-dimensional labeled data. Furthermore, almost all ANNS algorithms have been evaluated on labeled datasets whose labels are irrelevant to the data points themselves. However, in real-world applications, such as retrieval augmented generation (RAG) in large language models (LLMs), filtered retrieval is essential based on the features of each data point. Therefore, I decided to focus on improving an efficient graph-based ANNS algorithm, which serves as the baseline, to support filtering. I performed ablation studies, comparing the enhanced algorithm with other graph-based ANNS algorithms. Additionally, I generated a novel vector dataset as a benchmark for evaluating the filtering performance of each algorithm. The dataset's labels are closely related to each data point, making it more reasonable and convincing for modeling the application of similarity vector search in real-world fields like RAG. -->

<!-- ### Neural Architecture Search with Evolutionary Algorithms for Natural Language Processing

Currently, I am conducting research on Neural Architecture Search (NAS), as my senior design with my mentors — [Ruobin Wang](https://scholar.google.com/citations?user=oFAHM8QAAAAJ&hl=en&oi=sra) and [Lin Xu](https://scholar.google.com/citations?user=-PEahpMAAAAJ&hl=en&oi=sra). First developed by Google in 2017, NAS has gained popularity as many methods proposed in subsequent years save computational costs and allowed for the search of more efficient neural network architectures. However, I believe that the limitations of complex search strategies and restricted applications in research areas should be taken into consideration today. To address the first constraint, evolutionary algorithms are proposed. I have published a [conference paper](https://www.researchgate.net/publication/370983446_A_Parallel_Gannet_Optimization_Algorithm_with_Communication_Strategies_PGOA) about novel evolutionary algorithms, which not only offer simplicity in conception and execution, but also have many advantages such as efficient avoidance of local optima and boost the convergence speed; Secondly, it was noted that researchers prioritize benchmarking their models and pursue the SOTA on computer vision datasets like the CIFAR-10. Hence, it may be beneficial to develop novel benchmarking methods for NLP or LLMs, enabling one to fine-tune their models through adapter type and position variation, with subsequent evaluation of architecture performance. -->

<!-- ### Ethics and Safety of Large Language Models (LLMs)

Last quarter, I took [CS 222: Natural Language Processing](https://sites.google.com/ucr.edu/cs222-nlp/home) at UC, Riverside. The course covered various topics related to large language model (LLM) attacks and safety. For the final project, we were encouraged to explore novel ways to successfully attack publicly available LLMs. My project focused on enhancing adversarial attacks through chain of thought (CoT) prompting. Specifically, I combined gradient-based adversarial attack techniques with CoT prompting to study a universal and transferable adversarial CoT suffix capable of triggering the CoT ability in various LLMs. I implemented and evaluated this attack approach based on the existing codebase *llm-attacks*, running experiments to compare its performance against baseline methods and Amazon's *auto-cot*. Additionally, I evaluated the generated content using *Llama-Guard* and conducted ablation studies on various harmful types categorized by the tool. The experimental results demonstrated that my novel method successfully triggered the CoT ability on generation in multiple public aligned LLMs during attacks, outperforming prior approaches. -->
