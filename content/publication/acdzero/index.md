---
title: 'ACDZero: Graph-Embedding-Based Tree Search for Mastering Automated Cyber Defense'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yu Li
  - Sizhe Tang
  - admin
  - Fei Xu Yu
  - Guangyu Jiang
  - Mahdi Imani
  - Nathaniel D Bastian
  - Tian Lan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-01-01T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "**2026 IEEE International Conference on Computer Communications (INFOCOM) Workshop (Accepted)**"
publication_short: "**2026 IEEE International Conference on Computer Communications (INFOCOM) Workshop (Accepted)**"

abstract: ''

# Summary. An optional shortened abstract.
summary: ''

tags:
  - Cyber Defense
  - MCTS
  - Automated Defense

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/ACD_zero.pdf'
links:
- name: arXiv
  url: https://arxiv.org/html/2601.02196v2
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

**ACDZero** masters automated cyber defense by pairing Monte Carlo Tree Search with graph-neural-network embeddings of the network state — a planning-centric alternative to deep RL that achieves better defense reward, robustness, and sample efficiency.

**Key contributions:**

- Frames automated cyber defense as a POMDP and solves it with **MCTS guided by learned graph embeddings**, balancing exploration and exploitation.
- **GNN-based, permutation-invariant reasoning** over hosts and their relationships as attributed graphs.
- **Policy distillation with look-ahead planning**, yielding improved defense reward and robustness over state-of-the-art RL baselines across **CAGE Challenge 4** scenarios.

## BibTeX

```bibtex
@article{li2026acdzero,
  title={ACDZero: Graph-Embedding-Based Tree Search for Mastering Automated Cyber Defense},
  author={Li, Yu and Tang, Sizhe and Chen, Rongqian and Yu, Fei Xu and Jiang, Guangyu and Imani, Mahdi and Bastian, Nathaniel D and Lan, Tian},
  journal={arXiv preprint arXiv:2601.02196},
  year={2026}
}
```
