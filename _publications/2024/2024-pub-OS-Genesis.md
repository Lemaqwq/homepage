---
title:          "OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis"
date:           2024-12-27 00:01:00 +0800
selected:       true
pub:            "Preprint"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-danger">Arxiv</span>'
pub_date:       "2024"

abstract: >-
  Graphical User Interface (GUI) agents powered by Vision-Language Models (VLMs) have demonstrated human-like computer control capability. Despite their utility in advancing digital automation, a critical bottleneck persists: collecting high-quality trajectory data for training. Common practices for collecting such data rely on human supervision or synthetic data generation through executing pre-defined tasks, which are either resource-intensive or unable to guarantee data quality. Moreover, these methods suffer from limited data diversity and significant gaps between synthetic data and real-world environments. To address these challenges, we propose OS-Genesis, a novel GUI data synthesis pipeline that reverses the conventional trajectory collection process. Instead of relying on pre-defined tasks, OS-Genesis enables agents first to perceive environments and perform step-wise interactions, then retrospectively derive high-quality tasks to enable trajectory-level exploration. A trajectory reward model is then employed to ensure the quality of the generated trajectories. We demonstrate that training GUI agents with OS-Genesis significantly improves their performance on highly challenging online benchmarks. In-depth analysis further validates OS-Genesis's efficiency and its superior data quality and diversity compared to existing synthesis methods.


# cover:          assets/images/covers/HiddenKey.jpg
authors:
  - Qiushi Sun* 
  - Kanzhi Cheng*
  - Zichen Ding*
  - Chuanyang Jin*
  - Yian Wang
  - Fangzhi Xu
  - Zhenyu Wu
  - Liheng Chen
  - Chengyou Jia
  - Zhoumianze Liu
  - Ben Kao
  - Guohao Li
  - Junxian He
  - Yu Qiao
  - Zhiyong Wu

links:
  Website: https://qiushisun.github.io/OS-Genesis-Home
  Paper: https://arxiv.org/abs/2412.19723
  Code: https://github.com/OS-Copilot/OS-Genesis
  Checkpoints: https://huggingface.co/collections/OS-Copilot/os-genesis-6768d4b6fffc431dbf624c2d
  Data: https://huggingface.co/collections/OS-Copilot/os-genesis-6768d4b6fffc431dbf624c2d

badges:
  url: https://img.shields.io/github/stars/OS-Copilot/OS-Genesis
# Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
