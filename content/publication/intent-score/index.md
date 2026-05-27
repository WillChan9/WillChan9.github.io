---
title: 'IntentScore: Intent-Conditioned Action Evaluation for Computer-Use Agents'

# Authors
authors:
  - admin
  - Yu Li
  - Zeyu Fang
  - Sizhe Tang
  - Weidong Cao
  - Tian Lan

date: '2026-04-06T00:00:00Z'

publishDate: '2026-04-06T00:00:00Z'

publication_types: ['paper-preprint']

publication: "**arXiv preprint**"
publication_short: "**arXiv preprint**"

abstract: 'Computer-Use Agents (CUAs) leverage large language models to execute GUI operations on desktop environments, yet they generate actions without evaluating action quality, leading to irreversible errors that cascade through subsequent steps. We propose IntentScore, a plan-aware reward model that learns to score candidate actions from 398K offline GUI interaction steps spanning three operating systems. IntentScore trains with two complementary objectives: contrastive alignment for state-action relevance and margin ranking for action correctness. Architecturally, it embeds each candidate’s planning intent in the action encoder, enabling discrimination between candidates with similar actions but different rationales. IntentScore achieves 97.5% pairwise discrimination accuracy on held-out evaluation. Deployed as a re-ranker for Agent S3 on OSWorld, an environment entirely unseen during training, IntentScore improves task success rate by 6.9 points, demonstrating that reward estimation learned from heterogeneous offline trajectories generalizes to unseen agents and task distributions.'

summary: 'A plan-aware reward model for scoring and re-ranking candidate GUI actions for computer-use agents, trained on multi-OS offline trajectories and validated on OSWorld.'

tags:
  - Computer-Use Agents
  - Reward Model
  - GUI Agents

featured: false

url_pdf: ''
links: []
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

