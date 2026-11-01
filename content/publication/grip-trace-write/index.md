---
title: 'Grip, Trace, Write: Force-Aware Imitation and Reinforcement Learning for High-DoF Robotic Handwriting'

authors:
  - admin
  - Yiding Chen
  - Jijie Zhou
  - Tom Z. Jiahao

date: '2026-10-30T00:00:00Z'

publishDate: '2026-10-30T00:00:00Z'

publication_types: ['paper-conference']

publication: "**2026 Conference on Robot Learning (CoRL) Workshop PhysicalWM (Accepted)**"
publication_short: "**2026 Conference on Robot Learning (CoRL) Workshop PhysicalWM (Accepted)**"

abstract: 'Dexterous robotic handwriting with a freely held pen requires stable grasp retention, precise trajectory execution, and contact-force regulation in one coupled system. We present Grip, Trace, Write, a staged learning framework that first learns a reusable grasp controller, then trains a trajectory-conditioned writer from inverse-kinematics demonstrations, and finally improves writing through RL with rewards defined on task outcomes. A two-branch actor preserves the distinct roles of hand stabilization and arm–wrist motion while keeping both closed-loop through the shared state and pen dynamics. Across diverse tracing and writing tasks, the resulting policy improves completion, precision, force regulation, and execution efficiency over both behavior cloning and IK, and generalizes without fine-tuning to unseen English and Chinese content.'

summary: 'A staged imitation and reinforcement learning framework that lets a high-DoF dexterous hand write with a freely held pen, regulating grasp, trajectory, and contact force together.'

tags:
  - Dexterous Manipulation
  - Imitation Learning
  - Reinforcement Learning

featured: false

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://dexwriting.github.io/'
url_slides: ''
url_source: ''
url_video: ''

projects: []
slides: ""
---

## TL;DR

**Grip, Trace, Write** teaches a 25-DoF dexterous hand to write with a **freely held pen**, held by friction alone, while tracking both the stroke position and the requested contact force.

**Key contributions:**

- A **staged learning framework**: learn a reusable grasp controller, train a trajectory-conditioned writer from inverse-kinematics demonstrations, then improve it with RL on task-outcome rewards.
- A **two-branch actor** that separates hand stabilization from arm–wrist motion while keeping both closed-loop through the shared state and pen dynamics.
- Improves completion, precision, force regulation, and efficiency over behavior cloning and IK, and generalizes without fine-tuning to **unseen English and Chinese content**.

## BibTeX

```bibtex
@inproceedings{chen2026griptracewrite,
  title={Grip, Trace, Write: Force-Aware Imitation and Reinforcement Learning for High-DoF Robotic Handwriting},
  author={Chen, Rongqian and Chen, Yiding and Zhou, Jijie and Jiahao, Tom Z.},
  booktitle={CoRL 2026 Workshop PhysicalWM},
  year={2026}
}
```
