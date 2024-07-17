---
title:          "PRoLoRA: Partial Rotation Empowers More Parameter-Efficient LoRA"
date:           2024-05-12 00:01:00 +0800
selected:       true
pub:            "Annual Meeting of the Association for Computational Linguistics"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">ACL 2024</span>'
pub_date:       "2024"

abstract: >-
  With the rapid scaling of large language models (LLMs), serving numerous LoRAs concurrently has become increasingly impractical, leading to unaffordable costs and necessitating more parameter-efficient finetuning methods. In this work, we introduce Partially Rotation enhanced Low-Rank Adaptation (PRoLoRA), an intra-layer sharing mechanism comprising four essential components, broadcast reduction, rotation enhancement, partially-sharing refinement, and rectified initialization strategy. As a superset of LoRA, PRoLoRA pertains its advantages, and effectively circumvent the drawbacks of peer parameter-sharing methods with superior model capacity, practical feasibility, and broad applicability. Empirical experiments demonstrate the remarkably higher parameter efficiency of PRoLoRA in both specific parameter budget and performance target scenarios, and its scalability to larger LLMs. Notably, with one time less trainable parameters, PRoLoRA still outperforms LoRA on multiple instruction tuning datasets. Subsequently, an ablation study is conducted to validate the necessity of individual components and highlight the superiority of PRoLoRA over three potential variants. Hopefully, the conspicuously higher parameter efficiency can establish PRoLoRA as a resource-friendly alternative to LoRA.
# cover:          assets/images/covers/HiddenKey.jpg
authors:
  - Sheng Wang
  - Boyang Xue 
  - Jiacheng Ye
  - Jiyue Jiang
  - Liheng Chen
  - Lingpeng Kong
  - Chuan Wu
links:
  Paper: https://arxiv.org/abs/2402.16902
  Code: https://github.com/Forence1999/PRoLoRA.git
# Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
