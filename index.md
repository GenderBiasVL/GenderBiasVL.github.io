---
layout: home
title: GenderBiasVL
subtitle: "Can We Trust Off-the-shelf Deep Learning Models: On Benchmarking Backdoor Neuron Defects Localization"
---

## Abstract  

Pre-trained large deep learning models are now serving as the dominant component for downstream middleware users and have revolutionized the learning paradigm, replacing the traditional approach of training from scratch locally. To reduce development costs, developers often integrate third-party pre-trained deep neural networks (DNNs) into their intelligent software systems. However, utilizing untrusted DNNs presents significant security risks, as these models may contain intentional backdoor defects resulting from the black-box training process. These backdoor defects can be activated by hidden triggers, allowing attackers to maliciously control the model and compromise the overall reliability of the intelligent software. To ensure the safe adoption of DNNs in critical software systems, it is crucial to establish a comprehensive benchmark for backdoor defect analysis and localization. 

This paper addresses this research gap by introducing *BDefects4NN*, the first backdoor defect localization benchmark. *BDefects4NN* provides labeled backdoor-defected DNNs at the neuron level, facilitating the localization of defect root causes at the neuron granularity. Targeting the classical image classification task, we define three defect injection rules and employ four representative backdoor attacks across four popular network architectures and three widely adopted datasets, yielding a comprehensive database of 1,654 backdoor-defected DNNs with four defect quantities and varying infected neurons. Using our *BDefects4NN*, we conduct extensive experiments on evaluating six fault localization criteria (17.64% $WJI$) and two defect repair techniques (40.50% $ASRD$), which show limited effectiveness for backdoor defects. Additionally, we investigate backdoor-defected models in practical scenarios, specifically in lane detection for autonomous driving and large language models (LLMs), revealing potential threats and highlighting current limitations in accurate defect localization. This paper aims to raise awareness of the threats brought by backdoor defects in our community and inspire future advancements in fault localization methods. 

![](/assets/img/framework.png)

Overview of *BDefects4NN* framework. Targeting image classification task, our *BDefects4NN* designs three rules to inject neuron-level backdoors into DNNs and build 1,654 DNNs with backdoor defects, which can support the evaluation of fault localization methods and defect repair techniques.
