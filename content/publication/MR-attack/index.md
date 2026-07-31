---
title: 'A Neurosymbolic Framework for Interpretable Cognitive Attack Detection in Augmented Reality'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Allison Andreyev
  - Yanming Xiu
  - Mahdi Imani
  - Bin Li
  - Maria Gorlatova
  - Gang Tan
  - Tian Lan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-01-01T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "**Accepted by 2026 IEEE/CVF Conference on Computer Vision & Pattern Recognition (CVPR) Findings**"
publication_short: "**Accepted by 2026 IEEE/CVF Conference on Computer Vision & Pattern Recognition (CVPR) Findings**"

abstract: Augmented Reality (AR) enriches perception by overlaying virtual elements on the physical world. Due to its growing popularity, cognitive attacks that alter AR content to manipulate users' semantic perception have received increasing attention. Existing detection methods often focus on visual changes, which are restricted to pixel- or image-level processing and lack semantic reasoning capabilities, or they rely on pre-trained vision-language models (VLMs), which function as black-box approaches with limited interpretability. In this paper, we present CADAR, a novel neurosymbolic approach for cognitive attack detection in AR. It fuses multimodal vision-language inputs using neural VLMs to obtain a symbolic perception-graph representation, incorporating prior knowledge, salience weighting, and temporal correlations. The model then enables particle-filter based statistical reasoning -- a sequential Monte Carlo method -- to detect cognitive attacks. Thus, CADAR inherits the adaptability of pre-trained VLM and the interpretability and reasoning rigor of particle filtering. Experiments on an extended AR cognitive attack dataset show accuracy improvements of up to 10.7% over strong baselines on challenging AR attack scenarios, underscoring the promise of neurosymbolic methods for effective and interpretable cognitive attack detection.

# Summary. An optional shortened abstract.
summary: We developed a neurosymbolic framework for detecting and interpreting cognitive attacks in augmented reality systems.

tags:
  - Augmented Reality
  - Cognitive Attacks
  - Neurosymbolic AI
  - Security
  - Interpretability

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/A Neurosymbolic Framework for Interpretable Cognitive Attack Detection in Augmented Reality.pdf'
links:
- name: arXiv
  url: https://arxiv.org/abs/2508.09185
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: ''
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

## TL;DR

**CADAR** is a neurosymbolic framework for detecting *cognitive attacks* in Augmented Reality — attacks that alter AR content to manipulate what users perceive. It fuses neural vision-language perception with particle-filter-based statistical reasoning, inheriting the adaptability of pre-trained VLMs **and** the interpretability of Bayesian filtering.

**Key contributions:**

- A symbolic **perception-graph representation** fused from multimodal vision-language inputs, incorporating prior knowledge, salience weighting, and temporal correlations.
- **Particle-filter based statistical reasoning** (sequential Monte Carlo) over the perception graph for interpretable, rigorous attack detection.
- Accuracy improvements of up to **10.7%** over strong baselines on an extended AR cognitive-attack dataset.

## BibTeX

```bibtex
@misc{chen2025neurosymbolicframeworkinterpretablecognitive,
      title={A Neurosymbolic Framework for Interpretable Cognitive Attack Detection in Augmented Reality}, 
      author={Rongqian Chen and Allison Andreyev and Yanming Xiu and Mahdi Imani and Bin Li and Maria Gorlatova and Gang Tan and Tian Lan},
      year={2025},
      eprint={2508.09185},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2508.09185}, 
}
```
