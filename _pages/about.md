---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Greetings! I am Jingbo Su (Bob), a senior year college student major in Computer Science and Technology at the [North China University of Technology](http://www.ncut.edu.cn), Beijing, China. At present, I an participating in the [Graduate Preparation Program - Engineering](https://gpp.ucr.edu/engineering) at the [University of California, Riverside](https://www.ucr.edu) to complete my last undergraduate year.

## On-Going Research

<!-- ### Neural Architecture Search with Evolutionary Algorithms for Natural Language Processing

Currently, I am conducting research on Neural Architecture Search (NAS), as my senior design with my mentors — [Ruobin Wang](https://scholar.google.com/citations?user=oFAHM8QAAAAJ&hl=en&oi=sra) and [Lin Xu](https://scholar.google.com/citations?user=-PEahpMAAAAJ&hl=en&oi=sra). First developed by Google in 2017, NAS has gained popularity as many methods proposed in subsequent years save computational costs and allowed for the search of more efficient neural network architectures. However, I believe that the limitations of complex search strategies and restricted applications in research areas should be taken into consideration today. To address the first constraint, evolutionary algorithms are proposed. I have published a [conference paper](https://www.researchgate.net/publication/370983446_A_Parallel_Gannet_Optimization_Algorithm_with_Communication_Strategies_PGOA) about novel evolutionary algorithms, which not only offer simplicity in conception and execution, but also have many advantages such as efficient avoidance of local optima and boost the convergence speed; Secondly, it was noted that researchers prioritize benchmarking their models and pursue the SOTA on computer vision datasets like the CIFAR-10. Hence, it may be beneficial to develop novel benchmarking methods for NLP or LLMs, enabling one to fine-tune their models through adapter type and position variation, with subsequent evaluation of architecture performance. -->

### Ethics and Safety of Large Language Models (LLMs)

Last quarter, I took [CS 222: Natural Language Processing](https://sites.google.com/ucr.edu/cs222-nlp/home) at UC, Riverside. The course covered various topics related to large language model (LLM) attacks and safety. For the final project, we were encouraged to explore novel ways to successfully attack publicly available LLMs. My project focused on enhancing adversarial attacks through chain of thought (CoT) prompting. Specifically, I combined gradient-based adversarial attack techniques with CoT prompting to study a universal and transferable adversarial CoT suffix capable of triggering the CoT ability in various LLMs. I implemented and evaluated this attack approach based on the existing codebase *llm-attacks*, running experiments to compare its performance against baseline methods and Amazon's *auto-cot*. Additionally, I evaluated the generated content using *Llama-Guard* and conducted ablation studies on various harmful types categorized by the tool. The experimental results demonstrated that my novel method successfully triggered the CoT ability on generation in multiple public aligned LLMs during attacks, outperforming prior approaches.

### Efficient Graph-based Approximate Nearest Neighbor Search (ANNS)

Currently, I am conducting research on graph-based filtered ANNS as my senior research project at [UCR PAL](https://pal.cs.ucr.edu) at UC, Riverside. Existing ANNS algorithms do not have an efficient way to perform filtered search, especially on high-dimensional labeled data. Furthermore, almost all ANNS algorithms have been evaluated on labeled datasets whose labels are irrelevant to the data points themselves. However, in real-world applications, such as retrieval augmented generation (RAG) in large language models (LLMs), filtered retrieval is essential based on the features of each data point. Therefore, I decided to focus on improving an efficient graph-based ANNS algorithm, which serves as the baseline, to support filtering. I performed ablation studies, comparing the enhanced algorithm with other graph-based ANNS algorithms. Additionally, I generated a novel vector dataset as a benchmark for evaluating the filtering performance of each algorithm. The dataset's labels are closely related to each data point, making it more reasonable and convincing for modeling the application of similarity vector search in real-world fields like RAG.
