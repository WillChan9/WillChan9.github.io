---
title: 'Uncertainty Mitigation and Intent Inference: A Dual-Mode Human-Machine Joint Planning System'

authors:
  - Zeyu Fang
  - Yuxin Lin
  - Cheng Liu
  - Beomyeol Yu
  - Zeyuan Yang
  - admin
  - Taeyoung Lee
  - Mahdi Imani
  - Tian Lan

date: '2026-03-08T00:00:00Z'

publishDate: '2026-03-08T00:00:00Z'

publication_types: ['paper-preprint']

publication: "**arXiv preprint**"
publication_short: "**arXiv preprint**"

abstract: 'Effective human-robot collaboration in open-world environments requires joint planning under uncertain conditions. However, existing approaches often treat humans as passive supervisors, preventing autonomous agents from becoming human-like teammates that can actively model teammate behaviors, reason about knowledge gaps, query, and elicit responses through communication to resolve uncertainties. To address these limitations, we propose a unified human-robot joint planning system designed to tackle dual sources of uncertainty: task-relevant knowledge gaps and latent human intent. Our system operates in two complementary modes. First, an uncertainty-mitigation joint planning module enables two-way conversations to resolve semantic ambiguity and object uncertainty. It utilizes an LLM-assisted active elicitation mechanism and a hypothesis-augmented A* search, subsequently computing an optimal querying policy via dynamic programming to minimize interaction and verification costs. Second, a real-time intent-aware collaboration module maintains a probabilistic belief over the human''s latent task intent via spatial and directional cues, enabling dynamic, coordination-aware task selection for agents without explicit communication. We validate the proposed system in both Gazebo simulations and real-world UAV deployments integrated with a Vision-Language Model (VLM)-based 3D semantic perception pipeline. Experimental results demonstrate that the system significantly cuts the interaction cost by 51.9% in uncertainty-mitigation planning and reduces the task execution time by 25.4% in intent-aware cooperation compared to the baselines.'

summary: 'A dual-mode human-robot joint planning system for uncertainty mitigation (LLM-assisted elicitation and hypothesis-augmented planning) and real-time intent-aware UAV collaboration, validated in simulation and real-world deployments.'

tags:
  - Human-Robot Collaboration
  - UAV
  - Agent

featured: false

url_pdf: 'uploads/Uncertainty_Mitigation_and_Intent_Inference_A_Dual-Mode_Human-Machine_Joint_Planning_System.pdf'
links:
  - name: arXiv
    url: https://arxiv.org/abs/2603.07822
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

projects: []
slides: ""
---
