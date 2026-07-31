---
title: 'FlowEdit: Information-Theoretic Control of LLM Reasoning Flows for Ill-posed Problems Involving Conflicts'

# Authors
authors:
  - Sizhe Tang
  - Guangyu Jiang
  - Yu Li
  - admin
  - Ioannis G. Kevrekidis
  - Tian Lan

# NOTE: date is set for homepage ordering (4th position); hidden via hide_date.
# Actual arXiv submission: June 20, 2026.
date: '2026-03-01T00:00:00Z'
hide_date: true

publishDate: '2026-03-01T00:00:00Z'

publication_types: ['paper-preprint']

publication: "**arXiv preprint**"
publication_short: "**arXiv preprint**"

abstract: 'Large Language Models struggle with ill-posed problems that involve inconsistent conditions, conflicting statements, or mutually incompatible requirements. We propose FlowEdit, a framework that leverages information-theoretic principles to quantify and regulate the internal reasoning flows of LLMs, generating the full set of alternative responses under valid hypotheses. FlowEdit makes hidden conflicts explicit and maintains competing hypotheses via multiple reasoning branches, optimizing dual objectives: maximizing information flow from hypotheses to outcomes (flow sufficiency) while minimizing overlap across branches (flow separation). The mechanism operates through redistribution of next-token entropy within the model''s token stream. Extensive experiments demonstrate that FlowEdit outperforms leading proprietary models, improving exact-set-match accuracy by 68% while boosting overall response informativeness by 24%.'

summary: 'An information-theoretic framework that controls LLM internal reasoning flows to handle ill-posed, conflicting problems — maintaining competing hypotheses in parallel branches and returning the full set of valid answers.'

tags:
  - LLM Reasoning
  - Information Theory

featured: false

url_pdf: ''
links:
  - name: arXiv
    url: https://arxiv.org/abs/2607.20500
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

## TL;DR

**FlowEdit** gives LLMs a principled way to handle *ill-posed* problems — questions with conflicting or mutually incompatible conditions. Instead of silently collapsing onto one self-consistent hypothesis, it regulates the model's internal reasoning flows so that competing hypotheses survive in parallel branches, returning the **full set of valid answers** in a single pass.

**Key contributions:**

- An **information-theoretic control framework** for internal reasoning flows, with dual mutual-information objectives: **flow sufficiency** (maximize information from each hypothesis to its outcome) and **flow separation** (minimize overlap across branches).
- The mechanism operates by **redistributing next-token entropy** within the model's token stream, making hidden conflicts explicit.
- Outperforms leading proprietary models: **+68%** exact-set-match accuracy and **+24%** overall response informativeness.

## BibTeX

```bibtex
@misc{tang2026flowedit,
  title={FlowEdit: Information-Theoretic Control of LLM Reasoning Flows for Ill-posed Problems Involving Conflicts},
  author={Sizhe Tang and Guangyu Jiang and Yu Li and Rongqian Chen and Ioannis G. Kevrekidis and Tian Lan},
  year={2026},
  eprint={2607.20500},
  archivePrefix={arXiv},
  url={https://arxiv.org/abs/2607.20500},
}
```
