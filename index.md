---
layout: home
title: GenderBiasVL
subtitle: "Benchmarking Gender Bias in Vision Language Models via Counterfactual Probing"
---

## Abstract  

Large Vision-Language Models (LVLMs) have been widely adopted in various applications; however, they exhibit significant gender biases. Existing benchmarks primarily evaluate gender bias at the demographic group level, neglecting individual fairness, which emphasizes equal treatment of similar individuals. This research gap limits the detection of discriminatory behaviors, as individual fairness offers a more granular examination of biases that group fairness may overlook. For the first time, this paper introduces the *GenderBias-VL* benchmark to evaluate occupation-related gender bias in LVLMs using counterfactual visual questions under individual fairness criteria. 
To construct this benchmark, we first utilize text-to-image diffusion models to generate occupation images and their gender counterfactuals.
Subsequently, we generate corresponding textual occupation options by identifying stereotyped occupation pairs with high semantic similarity but opposite gender proportions in real-world statistics. This method enables the creation of large-scale visual question counterfactuals to expose biases in LVLMs, applicable in both multimodal and unimodal contexts through modifying gender attributes in specific modalities. Overall, our *GenderBias-VL* benchmark comprises 34,581 visual question counterfactual pairs,  covering 177 occupations. Using our benchmark, we extensively evaluate 15 commonly used open-source LVLMs (*e.g.*, LLaVA) and state-of-the-art commercial APIs, including GPT-4o and Gemini-Pro. Our findings reveal widespread gender biases in existing LVLMs. Our benchmark offers: (1) a comprehensive dataset for occupation-related gender bias evaluation; (2) an up-to-date leaderboard on LVLM biases; and (3) a nuanced understanding of the biases presented by these models.

![](/assets/img/framework.pdf)

Overview of *GenderBias-VL*. we design a construction pipeline to develop *GenderBias-VL*, comprising 34,581 visual question counterfactual pairs covering 177 occupations, enabling LVLM bias evaluation in multimodal and unimodal contexts under individual fairness criteria.
