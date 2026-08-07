---
title:          "OSReward: Instituting Standardized Evaluation for Cross-Platform Computer-Use Reward Models"
date:           2026-08-07 00:01:00 +0800
selected:       true
pub:            "Preprint"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-danger">Arxiv</span>'
pub_date:       "2026"

abstract: >-
  Computer-using agents (CUAs) are advancing rapidly across the digital world. A CUA trajectory records the agent's actions, states, and reasoning. Verifying whether it fulfilled the task instruction is central to CUA evaluation, data curation, and reinforcement learning. Neither human-written verifiers nor human annotators can provide such verification at scale, so the field increasingly turns to vision-language models (VLMs) as judges of CUA trajectories. But a fundamental question has long gone unexamined: are these VLM judges reliable enough? To study it systematically, we introduce OSReward, a realistic, high-quality benchmark that evaluates VLM judges on CUA trajectories. The trajectories come from diverse agent backbones executing human-verified instructions across platforms, and are then rigorously labeled with ground-truth verdicts through multi-stage human annotation. Building on it, we derive OSReward-Hard, a challenge set concentrating genuinely hard cases, and OSReward-Multi for fine-grained efficiency and alignment scoring. The most comprehensive evaluation of VLM judges to date finds even state-of-the-art models fall short of an ideal judge, sharing a systematic leniency bias that mislabels failed runs as successes. The few reliable enough to trust are too expensive to run at scale, while affordable open models trail far behind. To close this gap, we construct and release OS-Shepherd-100K, an open corpus of reasoning-annotated trajectory judgments for the CUA community. On it, we train OS-Shepherd (9B and 35B), open reward models that supply low-cost, stable, and reliable reward signals, matching commercial judges at 30-60x lower cost than the frontier. Extensive analyses further inform the design of reliable CUA reward at scale.


# cover:          assets/images/covers/HiddenKey.jpg
authors:
  - Qiushi Sun*
  - Kanzhi Cheng*
  - Yian Wang*
  - Bowen Yang*
  - Hang Yan*
  - Liheng Chen*
  - Fangzhi Xu
  - Zichen Ding
  - Nuo Chen
  - Jialin Cao
  - Xingdong Gong
  - Zehao Li
  - Kaiming Jin
  - Xinfeng Yuan
  - Zhoumianze Liu
  - Jingyang Gong
  - Zhangyue Yin
  - Jiahui Gao
  - Zhiyong Wu
  - Tianbao Xie
  - Jianbing Zhang
  - Ben Kao
  - Lingpeng Kong

links:
  Website: https://os-copilot.github.io/OSReward-Home/
  Paper: https://arxiv.org/abs/2607.28609
  Code: https://github.com/OS-Copilot/OSReward
  Data: https://huggingface.co/datasets/OS-Copilot/OS-Shepherd-100K
  Checkpoints: https://huggingface.co/collections/OS-Copilot/osreward-and-os-shepherd

badges:
  url: https://img.shields.io/github/stars/OS-Copilot/OSReward
---
