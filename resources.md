---
layout: default
title: Resources
nav_order: 7
---

# Course Resources
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Lecture Materials

- [Zotero export](papers/zotero.pdf) contains selected papers I've found on constrained and safe AI as of the first day of the course.
- [Zotero bib](papers/zotero-bib.pdf) contains bibliography entries only for the same papers.

### Lecture 1: Introduction
- [Lecture 1 slides](https://docs.google.com/presentation/d/1hWfI4J8VLtQBtpgG6QSIKgJv2suyiuWgN-y3B9Kfo9Q/edit?slide=id.g3b4d17a504e_0_10#slide=id.g3b4d17a504e_0_10)
- [Applications lecture notes](lec/lec1/applications.pdf)
- [Applications slides]()
- [Foundational concepts slides](lec/lec1/Lagrangian_and_Repair_Hard_Constraints.pdf)
- [How to give a talk](lec/how-to-give-a-talk.pdf)

#### Lecture 1 Papers
<!-- - [Constrained Deep Learning Duality](lec/lec1/Constrained_Deep_Learning_Duality.pdf)
- [Constrained AI Frontiers](lec/lec1/Constrained_AI_Frontiers.pdf)
- [Lagrangian and Repair Hard Constraints](lec/lec1/Lagrangian_and_Repair_Hard_Constraints.pdf) -->
- [Adopt Constraints Over Penalties (Ramirez et al., 2025)](lec/lec1/2505.20628v3.pdf)
- [Optimization Learning (Van Hentenryck, 2025)](lec/lec1/2501.03443v1.pdf)
<!-- - [HardNet Paper (Min & Azizan, 2025)](lec/lec1/2410.10807v4%20(1).pdf) -->
- [Fioretto & Van Hentenryck (2020)](lec/lec1/2001.09394v2.pdf)
<!-- - [Boyd & Vandenberghe Convex Optimization Book](lec/lec1/bv_cvxbook.pdf) -->

# Reference Papers by Topic

## 1/6/2026 Lagrangian methods

* **[1] Position: Adopt Constraints Over Penalties in Deep Learning** — Juan Ramirez, Meraj Hashemizadeh, Simon Lacoste-Julien (2025). *arXiv preprint*. arXiv:2505.20628; DOI: 10.48550/arXiv.2505.20628.
  Argues that penalty methods are often unreliable for enforcing constraints in deep learning and advocates constraint-first training (for example via Lagrangian methods) to achieve trustworthy behavior.
* **[7] Lagrangian Duality for Constrained Deep Learning** — Ferdinando Fioretto, Pascal Van Hentenryck, Terrence W K Mak, Cuong Tran, Federico Baldo, Michele Lombardi (2020). *arXiv preprint*. arXiv:2001.09394; DOI: 10.48550/arXiv.2001.09394.
  Applies Lagrangian duality to train deep networks under hard constraints across domains such as energy systems and fairness, enabling improved solutions with principled constraint handling.
* **[19] Lagrangian Duality for Constrained Deep Learning** — Ferdinando Fioretto, Pascal Van Hentenryck, Terrence W K Mak, Cuong Tran, Federico Baldo, Michele Lombardi (2020). *arXiv preprint (duplicate Zotero record)*. arXiv:2001.09394; DOI: 10.48550/arXiv.2001.09394.
  Applies Lagrangian duality to train deep networks under hard constraints across domains such as energy systems and fairness, enabling improved solutions with principled constraint handling.
* **[23] Chance constraint Optimization Learning** — Pascal Van Hentenryck, Ian Stainwright, Shmuel P Rubin, Kevin Duffy (2025). *arXiv preprint*. arXiv:2501.03443; DOI: 10.48550/arXiv.2501.03443.
  Introduces an optimization-learning perspective for chance-constrained problems, learning solution mappings and risk measures for applications such as security-constrained optimal power flow.
* **[21] Chance-Constrained Optimization (Stanford EE364a lecture notes)** — Stephen Boyd (n.d.). *Course notes (Stanford EE364a)*. URL: `https://web.stanford.edu/class/ee364a/lectures/chance_constr.pdf`.
  Lecture-note style introduction to chance-constrained optimization that develops probabilistic constraint formulations and standard convex or dual approximations.
* **[22] Chance-Constrained Optimization lecture notes (PDF attachment)** — Stanford EE364a (n.d.). *Course notes PDF*. URL: `https://web.stanford.edu/class/ee364a/lectures/chance_constr.pdf`.
  A direct PDF attachment of the Stanford EE364a chance-constrained optimization lecture material used as a reference for chance constraints.

## 1/20/2026 Differentiable projections

* **[2] Enforcing Hard Linear Constraints in Deep Learning Models with Decision Rules** — Gonzalo E. Constante-Flores, Hao Chen, Can Li (2025). *arXiv preprint*. arXiv:2505.13858; DOI: 10.48550/arXiv.2505.13858.
  Proposes a model-agnostic architecture that enforces input-dependent hard linear constraints via decision rules, providing formal constraint satisfaction while maintaining competitive accuracy and low latency.
* **[4] HardNet: Hard-Constrained Neural Networks with Universal Approximation Guarantees** — Soobin Min, Navid Azizan (2025). *arXiv preprint*. arXiv:2410.10807; DOI: 10.48550/arXiv.2410.10807.
  Introduces HardNet, a hard-constrained neural network construction that exactly satisfies multiple input-dependent inequality constraints while retaining universal approximation guarantees.
* **[18] HardNet: Hard-Constrained Neural Networks with Universal Approximation Guarantees** — Soobin Min, Navid Azizan (2025). *arXiv preprint*. arXiv:2410.10807; DOI: 10.48550/arXiv.2410.10807.
  Introduces HardNet, a hard-constrained neural network construction that exactly satisfies multiple input-dependent inequality constraints while retaining universal approximation guarantees.
* **[28] OptNet: Differentiable Optimization as a Layer in Neural Networks** — Brandon Amos, Lei Xu, J. Zico Kolter (2021). *arXiv preprint*. arXiv:1703.00443; DOI: 10.48550/arXiv.1703.00443.
  Introduces OptNet, a differentiable optimization layer that embeds quadratic programs in neural networks and enables end-to-end training via differentiable solvers.
* **[35] BarrierNet: Differentiable Control Barrier Functions for Learning of Safe Robot Control** — Ames, Aaron D, Xu, Xiangru, Grizzle, Jessy W, Tabuada, Paulo, et al. (2019). *IEEE Transactions on Robotics, 35 (5) pp. 1107-1123*. DOI: 10.1109/TRO.2019.2944364.
  Introduces BarrierNet, which integrates differentiable control barrier functions into learning to produce controllers with formal safety guarantees.
* **[38] BarrierNet: Differentiable Control Barrier Functions for Learning of Safe Robot Control** — Ames, Aaron D, Xu, Xiangru, Grizzle, Jessy W, Tabuada, Paulo, et al. (2020). *IEEE Transactions on Robotics, 35 (5) pp. 1107-1123*. DOI: 10.1109/TRO.2019.2944364.
  Introduces BarrierNet, which integrates differentiable control barrier functions into learning to produce controllers with formal safety guarantees.
* **[36] Differentiable Control Barrier Functions for Vision-based End-to-End Autonomous Driving** — Yixiao Guo, Anirudha Majumdar (2022). *arXiv preprint*. arXiv:2203.10971; DOI: 10.48550/arXiv.2203.10971.
  Introduces differentiable control barrier functions for vision-based end-to-end autonomous driving, coupling perception with a safety-certified control layer.
* **[39] Differentiable Control Barrier Functions for Vision-based End-to-End Autonomous Driving** — Yixiao Guo, Anirudha Majumdar (2022). *arXiv preprint*. arXiv:2203.10971; DOI: 10.48550/arXiv.2203.10971.
  Introduces differentiable control barrier functions for vision-based end-to-end autonomous driving, coupling perception with a safety-certified control layer.

## 1/27/2026 Reinforcement learning

* **[29] Constrained Policy Optimization** — Joshua Achiam, David Held, Aviv Tamar, Pieter Abbeel (2017). *arXiv preprint*. arXiv:1705.10528; DOI: 10.48550/arXiv.1705.10528.
  Introduces Constrained Policy Optimization, a trust-region reinforcement learning algorithm with theoretical motivation for monotonic improvement under constraints.
* **[26] Projection-Based Constrained Policy Optimization** — Weiwei Cheng, Pengfei Ren, Tianyang Lu, Mingyuan Liu, Bo Dai, et al. (2021). *arXiv preprint*. arXiv:2010.03152; DOI: 10.48550/arXiv.2010.03152.
  Proposes Projection-Based Constrained Policy Optimization, enforcing constraints by projecting policy updates into the feasible set for improved stability in constrained reinforcement learning.
* **[27] First Order Constrained Optimization in Policy Space** — Weiwei Cheng, Bo Dai, Zhenjie Zhang, Jia Liu, Zhuoran Yang (2020). *arXiv preprint*. arXiv:2002.06506; DOI: 10.48550/arXiv.2002.06506.
  Introduces a scalable first-order method for constrained optimization in policy space that aims to satisfy constraints while avoiding costly second-order computations.
* **[41] Safe Exploration in Continuous Action Spaces** — Gregory Dalal, Krishnamurthy Dvijotham, Matej Vecerik, Todd Hester, Cosmin Paduraru, Yuval Tassa (2018). *arXiv preprint*. arXiv:1801.08757; DOI: 10.48550/arXiv.1801.08757.
  Introduces a safe exploration method for continuous-action reinforcement learning that enforces state constraints during learning and avoids the violations common in reward-shaping baselines.

## 2/3/2026 Reinforcement learning

* **[6] Distributionally Robust Constrained Reinforcement Learning under Strong Duality** — Bo Zhang, Amy Zhang, Sangwon Kim, Matthew O. Jackson, Karan Singhal, et al. (2024). *arXiv preprint*. arXiv:2406.15788; DOI: 10.48550/arXiv.2406.15788.
  Develops a strong-duality-based framework for distributionally robust constrained reinforcement learning with convergence guarantees and highlights failure modes of existing iterative methods.
* **[37] End-to-End Safe Reinforcement Learning through Barrier Functions for Safety-Critical Continuous Control Tasks** — Gautham K. Gopalakrishnan, Arnold L. Springer, Catherine J. Sun (2021). *arXiv preprint*. arXiv:2103.13464; DOI: 10.48550/arXiv.2103.13464.
  Proposes an end-to-end safe reinforcement learning approach that uses barrier functions to maintain safety during training in continuous-control tasks.
* **[32] A General Safety Framework for Learning-Based Control in Uncertain Robotic Systems** — Katherine E. Driggs-Campbell, Rachel Holladay, Rahil Shome, Mauricio Arcak (2024). *arXiv preprint*. arXiv:2406.05655; DOI: 10.48550/arXiv.2406.05655.
  Presents a general framework for safe learning-based control under uncertainty that combines learning with safety guarantees to ensure correct operation during and after training.
* **[40] A General Safety Framework for Learning-Based Control in Uncertain Robotic Systems** — Katherine E. Driggs-Campbell, Rachel Holladay, Rahil Shome, Mauricio Arcak (2025). *arXiv preprint*. arXiv:2406.05655; DOI: 10.48550/arXiv.2406.05655.
  Presents a general framework for safe learning-based control under uncertainty that combines learning with safety guarantees to ensure correct operation during and after training.
* **[33] One Filter to Deploy Them All: Robust Safety for Quadrupedal Navigation in Unknown Environments** — Aman S. Abhishek, Nils Wagener, Matthew O. Jackson, Karan Singhal, et al. (2025). *arXiv preprint*. arXiv:2501.19503; DOI: 10.48550/arXiv.2501.19503.
  Proposes a robust safety filter for quadrupedal navigation that can be deployed across unknown environments to provide safe behavior while preserving performance.

## 2/10/2026 LLM alignment

* **[20] Advancing LLM Safe Alignment with Safety Representation Ranking** — Tianqi Du, Zeming Wei, Quan Chen, Chenheng Zhang, Yisen Wang (2025). *arXiv preprint (ICLR 2026 submission)*. arXiv:2505.15710; DOI: 10.48550/arXiv.2505.15710. ([arXiv][1])
  Proposes Safety Representation Ranking, which ranks multiple candidate responses using internal LLM representations to select safer outputs at inference time without changing model weights.
* **[31] Learning Safety Constraints for Large Language Models** — Jianwei Zhang, Qiming Zhu, Yifang Xu, Mingjie Zhao, Hengrui Zhao, et al. (2025). *arXiv preprint*. arXiv:2504.17446; DOI: 10.48550/arXiv.2504.17446.
  Proposes Safety Polytope, a geometric method that learns linear safety constraints in LLM representation space to improve safety generalization and robustness to jailbreak prompts.
* **[42] Learning Safety Constraints for Large Language Models** — Jianwei Zhang, Qiming Zhu, Yifang Xu, Mingjie Zhao, Hengrui Zhao, et al. (2025). *arXiv preprint*. arXiv:2504.17446; DOI: 10.48550/arXiv.2504.17446.
  Proposes Safety Polytope, a geometric method that learns linear safety constraints in LLM representation space to improve safety generalization and robustness to jailbreak prompts.
* **[12] Persona Vectors: Monitoring and Controlling Character Traits in Language Models** — Alex Schiebel, Wentao Li, Andrew Huang, Taylor Berg-Kirkpatrick, David Bau, et al. (2025). *arXiv preprint*. arXiv:2507.21509; DOI: 10.48550/arXiv.2507.21509.
  Identifies linear 'persona vectors' in large language model representations that enable monitoring and steering of character traits during generation.
* **[3] On Surjectivity of Neural Networks: Can you elicit any behavior from your model?** — Haozhe Jiang, Nika Haghtalab (2025). *arXiv preprint*. arXiv:2508.19445; DOI: 10.48550/arXiv.2508.19445.
  Shows that many common neural network architectures are (almost) surjective, implying that an adversary can in principle elicit essentially any specified output behavior from a trained model.

## 2/17/2026 Post-training interventions

* **[13] AlphaEdit: Null-Space Constrained Knowledge Editing for Language Models** — Pei Ke, Fei Mi, Jingkun Liu, Huaiyu Zhu, Sun, et al. (2025). *arXiv preprint*. arXiv:2410.02355; DOI: 10.48550/arXiv.2410.02355.
  Proposes AlphaEdit, a knowledge-editing method that constrains weight updates to a null space so targeted edits minimally disrupt other model behaviors.
* **[17] Guiding LLMs The Right Way: Fast, Non-Invasive Constrained Generation** — Luca Beurer-Kellner, Marc Fischer, Martin Vechev (2024). *arXiv preprint*. arXiv:2403.06988; DOI: 10.48550/arXiv.2403.06988. ([arXiv][2])
  Presents DOMINO, a constrained decoding algorithm that aligns subword vocabularies with formal constraints and uses precomputation and speculative decoding to achieve near-zero overhead.

## 2/24/2026 Formal verification

* **[11] Hilbert: Prompting Large Language Models to Formalize Theories using Recursive Proving** — Anonymous (2025). *arXiv preprint*. arXiv:2509.22819; DOI: 10.48550/arXiv.2509.22819.
  Introduces Hilbert, a prompting framework that treats natural-language proofs as recursive programs to generate machine-checkable formal proofs with informal reasoning guidance.
* **[30] Backpropagation through Signal Temporal Logic Specifications: Infusing Logical Structure into Gradient-Based Methods** — Aditya Prabhakar, Subhro Das, Siavash R. Lemay, Supratik Paul, et al. (2025). *arXiv preprint*. arXiv:2509.19062; DOI: 10.48550/arXiv.2509.19062.
  Develops differentiable surrogates for Signal Temporal Logic specifications to enable gradient-based learning that directly optimizes temporal-logic satisfaction.
* **[34] Scalable Learning of Safety Guarantees for Autonomous Systems using Hamilton-Jacobi Reachability** — HJReachability Team (2022). *arXiv preprint*. arXiv:2210.16206; DOI: 10.48550/arXiv.2210.16206.
  Develops scalable approaches to learn Hamilton–Jacobi reachability-based safety certificates with neural approximations, enabling safety guarantees in higher-dimensional systems.

## 3/3/2026 Declarative programming & tool use

* **[5] OptiMind: Teaching LLMs to Think Like Optimization Experts** — Hao Chen, Zixin Zhu, Dhruba Ray, Neel Sahoo, Neha Nayyar, et al. (2025). *Document ([www.microsoft.com](http://www.microsoft.com))*. URL: `https://www.microsoft.com/en-us/research/publication/optimind-teaching-llms-to-think-like-optimization-experts/`.
  Presents OptiMind, an LLM-assisted framework for formulating optimization problems from natural language that improves accuracy through data cleaning, task decomposition, and iterative refinement.
* **[8] OptiMUS-0.3** — Hamidreza AhmadiTeshnizi, Farhad Babaei, Vladimir Bergman, Maxim Bilenko, et al. (2025). *arXiv preprint*. arXiv:2407.19633; DOI: 10.48550/arXiv.2407.19633.
  Introduces OptiMUS, a modular LLM agent system and benchmark that converts natural-language optimization problems into executable linear or mixed-integer programs with automated debugging and evaluation.
* **[9] OptiChat: A Conversational Agent for Optimization Modeling** — Hao Chen, Dhruba Ray, Neel Sahoo, Lucas Leyton-Brown (2025). *arXiv preprint*. arXiv:2501.08406; DOI: 10.48550/arXiv.2501.08406.
  Introduces OptiChat, a conversational assistant that helps users build, interpret, and solve optimization models by combining LLM dialogue with solver-backed computation.
* **[10] Large Language Models for Supply Chain Decisions** — Francesca Cianchi, Zongzhang Zhang, Tinglong Dai, Nilesh M. Patil (2025). *arXiv preprint*. arXiv:2506.03078; DOI: 10.48550/arXiv.2506.03078.
  Explores how large language models can be integrated with operations research workflows for supply chain decision-making, emphasizing both capabilities and practical limitations.
* **[14] SWE-bench: Can Language Models Resolve Real-World GitHub Issues?** — John Yang, Carlos Jimenez, Alexander Wettig, Kilian Lieret, et al. (2023). *arXiv preprint*. arXiv:2310.06770; DOI: 10.48550/arXiv.2310.06770.
  Introduces SWE-bench, a benchmark of real GitHub issues with tests that measures whether language models can produce correct code changes in existing repositories.
* **[24] Decoding the Configuration of AI Coding Agents: Insights from Claude Code projects** — Madeline Zucker, Annie Rauwerdink, Colton Aldridge, Kenneth Chan, et al. (2025). *arXiv preprint*. arXiv:2511.09268; DOI: 10.48550/arXiv.2511.09268.
  Empirically analyzes configuration practices in Claude Code projects and derives patterns for instructing and structuring agentic coding workflows.
* **[25] Claude Code Best Practices** — Anthropic (2025). *Engineering blog post*. URL: `https://www.anthropic.com/engineering/claude-code-best-practices`. ([Anthropic][3])
  Provides practical guidance for using Claude Code effectively, including context-file conventions, tool allowlists, and workflow tips for safer agentic coding.

## 3/10/2026 Synthesis and future directions

* **[15] GDPval: Evaluating AI Model Performance on Real-World Economically Valuable Tasks** — Weijia Shi, Shuyue Hu, Houzheng Chen, Ziru Chen, et al. (2025). *arXiv preprint*. arXiv:2510.04374; DOI: 10.48550/arXiv.2510.04374.
  Proposes GDPval, an evaluation framework and dataset for measuring AI performance on real-world economically valuable tasks using outcome-linked metrics.
* **[16] Democratizing Optimization with Generative AI** — David Simchi-Levi, Tinglong Dai, Karan Singhal, Michelle L. Zhang, Shellye Xiao Wu (2025). *SSRN preprint*. DOI: 10.2139/ssrn.5511218. ([ResearchGate][4])
  Argues that generative AI can broaden access to optimization by translating natural-language problem descriptions into formal models and interactive decision-support workflows.

[1]: https://arxiv.org/abs/2505.15710 "[2505.15710] Advancing LLM Safe Alignment with Safety Representation Ranking"
[2]: https://arxiv.org/abs/2403.06988 "[2403.06988] Guiding LLMs The Right Way: Fast, Non-Invasive Constrained Generation"
[3]: https://www.anthropic.com/engineering/claude-code-best-practices "Claude Code Best Practices \ Anthropic"
[4]: https://www.researchgate.net/publication/395817441_Democratizing_Optimization_with_Generative_AI "Democratizing Optimization with Generative AI | Request PDF"

<!-- 




### Lagrangian Methods
- [Fioretto & Van Hentenryck (2020)](papers/lagrangian%20methods/2001.09394v2.pdf)

### Chance Constraints
- [Chance-Constrained Optimization (Boyd)](papers/chance%20constraints/chance_constr.pdf)
- [Nemirovski & Shapiro: Convex Approximations](papers/chance%20constraints/Nemirovski_Shapiro.pdf)
- [Rockafellar & Uryasev: CVaR Optimization](papers/chance%20constraints/Rockafellar_Uryasev.pdf)

### Projections
- [Projections Reference](papers/projections.pdf)

---

## Additional Resources

### Course Links
- [Live Schedule (Google Sheets)](https://docs.google.com/spreadsheets/d/1qYS6aMa5TyBz1OmN1CT787XdBiAisVg9pACr-XSaN9A/edit?gid=0#gid=0)
- [Office Hours Calendar](https://calendar.app.google/sCu1wpZXkUdAXdA59)
- [Zoom Meeting Room](https://stanford.zoom.us/j/6394072382?pwd=bndKcXBpRFdOb2x5VFhuT0kzN1QvQT09)

### Useful Links
- [Stanford Campus Map](https://campus-map.stanford.edu/?srch=McCullough+122)
- [Boyd's EE 364a Course Materials](https://web.stanford.edu/class/ee364a/) -->
