---
title:          "LoRA Meets Dropout under a Unified Framework"
date:           2024-02-12 00:01:00 +0800
selected:       true
pub:            "Annual Meeting of the Association for Computational Linguistics"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">ACL 2024</span>'
pub_date:       "2024"

abstract: >-
  With the remarkable capabilities, large language models (LLMs) have emerged as essential elements in numerous NLP applications, while parameter-efficient finetuning, especially LoRA, has gained popularity as a lightweight approach for model customization. Meanwhile, various dropout methods, initially designed for full finetuning with all the parameters updated, alleviates overfitting associated with excessive parameter redundancy. Hence, a possible contradiction arises from negligible trainable parameters of LoRA and the effectiveness of previous dropout methods, which has been largely overlooked. To fill this gap, we first confirm that parameter-efficient LoRA is also overfitting-prone. We then revisit transformerspecific dropout methods, and establish their equivalence and distinctions mathematically and empirically. Building upon this comparative analysis, we introduce a unified framework for a comprehensive investigation, which instantiates these methods based on dropping position, structural pattern and compensation measure. Through this framework, we reveal the new preferences and performance comparisons of them when involved with limited trainable parameters. This framework also allows us to amalgamate the most favorable aspects into a novel dropout method named HiddenKey. Extensive experiments verify the remarkable superiority and sufficiency of HiddenKey across multiple models and tasks, which highlights it as the preferred approach for high-performance and parameter-efficient finetuning of LLMs.
# cover:          assets/images/covers/HiddenKey.jpg
authors:
  - Sheng Wang*
  - Liheng Chen*
  - Jiyue Jiang
  - Boyang Xue
  - Lingpeng Kong
  - Chuan Wu
links:
  Paper: https://arxiv.org/abs/2403.00812
# Code: https://github.com/luost26/academic-homepage
# Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
