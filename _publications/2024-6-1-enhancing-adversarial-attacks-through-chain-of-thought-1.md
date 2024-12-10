---
title: "Enhancing Adversarial Attacks through Chain of Thought"
collection: publications
permalink: /publication/2024-6-1-enhancing-adversarial-attacks-through-chain-of-thought-1
excerpt: 'This paper enhances adversarial attacks on aligned LLMs by integrating chain of thought prompts with the greedy coordinate gradient technique, improving attack robustness and transferability, and evaluating harmful interactions using Llama Guard.'
date: 2024-06-01
venue: 'arXiv preprint'
# paperurl: 'https://www.researchgate.net/publication/370983446_A_Parallel_Gannet_Optimization_Algorithm_with_Communication_Strategies_PGOA'
citation: 'Su, Jingbo. &quot;Enhancing Adversarial Attacks through Chain of Thought.&quot; <i>arXiv preprint</i> arXiv:2410.21791 (2024).'
---

<!-- [![Paper](https://img.shields.io/badge/Paper-10.1007-blue)](https://link.springer.com/chapter/10.1007/978-981-99-0105-0_7) -->
[![Paper](https://img.shields.io/badge/Paper-arXiv-red)](https://arxiv.org/abs/2410.21791)
[![Code](https://img.shields.io/badge/Code-LLM.Attack-green)](https://github.com/sujingbo0217/CS222W24-LLM-Attack)

**Author:** Jingbo Su  
*North China University of Technology*  
*University of California, Riverside*

### Abstract

> Large language models (LLMs) have demonstrated impressive performance across various domains but remain susceptible to safety concerns. Prior research indicates that gradient-based adversarial attacks are particularly effective against aligned LLMs and the chain of thought (CoT) prompting can elicit desired answers through step-by-step reasoning.
This paper proposes enhancing the robustness of adversarial attacks on aligned LLMs by integrating CoT prompts with the greedy coordinate gradient (GCG) technique. Using CoT triggers instead of affirmative targets stimulates the reasoning abilities of backend LLMs, thereby improving the transferability and universality of adversarial attacks.
We conducted an ablation study comparing our CoT-GCG approach with Amazon Web Services *auto-cot*. Results revealed our approach outperformed both the baseline GCG attack and CoT prompting. Additionally, we used *Llama Guard* to evaluate potentially harmful interactions, providing a more objective risk assessment of entire conversations compared to matching outputs to rejection phrases.

### Keywords

> LLM safety, Adversarial attacks, Gradient-based attacks, Chain of thought, Llama guard.

### Download

[Enhancing Adversarial Attacks through Chain of Thought](https://sujingbo0217.github.io/files/srw24.pdf)
