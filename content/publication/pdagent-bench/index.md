---
title: 'PDAGENT-BENCH: Characterizing, Grounding, and Architecting LLM/VLM Agents for VLSI Physical Design'

# Authors
authors:
  - Qiufeng Li
  - admin
  - Quan Cheng
  - Chengxuan Wang
  - Sizhe Tang
  - Chia-Tung Ho
  - David Z. Pan
  - Tian Lan
  - Weidong Cao

date: '2026-06-15T00:00:00Z'

publishDate: '2026-06-15T00:00:00Z'

publication_types: ['paper-preprint']

publication: "**arXiv preprint**"
publication_short: "**arXiv preprint**"

abstract: 'Modern chip physical design is a complex, multi-stage workflow that remains a promising yet underexplored domain for LLM/VLM-based agents. We introduce PDAGENT-BENCH, a comprehensive and multi-dimensional benchmark for evaluating LLM/VLM-based agents across the physical design stack. The benchmark suite contains 353 curated problems that combine conceptual questions with real-world industrial artifacts, with expert-validated references and executable solutions, providing standardized evaluation across multiple design stages. Our evaluation of 11 frontier LLMs/VLMs reveals a substantial gap between conceptual understanding and tool-grounded execution (e.g., 42.2% on Innovus script generation). We further present an agentic workflow framework that enhances performance through human-skill integration, and release the benchmark with open-source process design kits and EDA tools. We anticipate PDAGENT-BENCH will accelerate the development of domain-specific LLM/VLM agents for this high-impact domain.'

summary: 'PDAGENT-BENCH is a comprehensive benchmark of 353 curated problems for evaluating LLM/VLM agents across the VLSI physical design stack, revealing a substantial gap between conceptual understanding and tool-grounded execution.'

tags:
  - LLM Agents
  - VLSI Physical Design
  - Benchmark

featured: false

url_pdf: ''
links:
  - name: arXiv
    url: https://arxiv.org/abs/2606.17253
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

**PDAGENT-BENCH** is the first comprehensive, multi-dimensional benchmark for evaluating LLM/VLM-based agents across the VLSI **physical design** stack. Frontier models handle the *concepts* well but stumble badly when they have to actually drive EDA tools.

**Key contributions:**

- **353 curated problems** spanning the physical design stack, combining conceptual questions with real-world industrial artifacts, each with expert-validated references and executable solutions.
- A systematic evaluation of **11 frontier LLMs/VLMs**, revealing a substantial gap between conceptual understanding and tool-grounded execution — e.g. only **42.2%** on Innovus script generation.
- An **agentic workflow framework** that improves performance through human-skill integration.
- Open-source release with process design kits and EDA tools for standardized, reproducible evaluation.

## BibTeX

```bibtex
@misc{li2026pdagentbench,
  title={PDAGENT-BENCH: Characterizing, Grounding, and Architecting LLM/VLM Agents for VLSI Physical Design},
  author={Qiufeng Li and Rongqian Chen and Quan Cheng and Chengxuan Wang and Sizhe Tang and Chia-Tung Ho and David Z. Pan and Tian Lan and Weidong Cao},
  year={2026},
  eprint={2606.17253},
  archivePrefix={arXiv},
  url={https://arxiv.org/abs/2606.17253},
}
```
