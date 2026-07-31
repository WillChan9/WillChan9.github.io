---
title: 'Agent Alpha: Tree Search Unifying Generation, Exploration and Evaluation for Computer-Use Agents'

# Authors
authors:
  - Sizhe Tang
  - admin
  - Tian Lan

date: '2026-02-03T00:00:00Z'

publishDate: '2026-02-03T00:00:00Z'

publication_types: ['paper-conference']

publication: "**2026 Conference on Language Modeling (COLM) (Accepted)**"
publication_short: "**2026 Conference on Language Modeling (COLM) (Accepted)**"

abstract: 'While scaling test-time compute through trajectory-level sampling has significantly improved Graphical User Interface (GUI) agents, the lack of regressive ability prevents the reuse of partial successes and the recovery from early missteps. In this paper, we introduce Agent Alpha, a unified framework that synergizes generation, exploration, and evaluation through step-level Monte Carlo Tree Search (MCTS). It enables active modeling or exploiting structures of the planning space. By integrating alpha-UCT guided search into the interaction loop, Agent Alpha enables deliberate planning, facilitating early pruning of suboptimal branches and efficient prefix reuse. We also employ comparison-driven evaluation to mitigate absolute scoring biases and diversity-constrained expansion to maintain a compact, informative search space. Regret bound of alpha-UCT is analyzed. On the OS-World benchmark, Agent Alpha achieves a state-of-the-art success rate of ∼77%, significantly outperforming trajectory-level baselines under equivalent compute.'

summary: 'We introduce Agent Alpha, a unified framework that synergizes generation, exploration, and evaluation through step-level MCTS for computer-use agents, achieving state-of-the-art on OS-World.'

tags:
  - Computer-Use Agents
  - MCTS
  - GUI Agents

featured: false

url_pdf: 'uploads/Agent_Alpha.pdf'
links:
  - name: arXiv
    url: https://arxiv.org/abs/2602.02995
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

**Agent Alpha** unifies generation, exploration, and evaluation for computer-use agents through **step-level MCTS**: instead of sampling whole trajectories, it plans deliberately at every step — pruning suboptimal branches early and reusing successful prefixes. State-of-the-art **~77%** success on OSWorld.

**Key contributions:**

- **Alpha-UCT guided step-level tree search** integrated into the GUI interaction loop, with a regret-bound analysis.
- **Comparison-driven evaluation** to mitigate absolute scoring biases, and **diversity-constrained expansion** to keep the search space compact and informative.
- State-of-the-art **~77%** success rate on the OSWorld benchmark, significantly outperforming trajectory-level baselines under equivalent compute.

## BibTeX

```bibtex
@misc{tang2026agentalpha,
      title={Agent Alpha: Tree Search Unifying Generation, Exploration and Evaluation for Computer-Use Agents},
      author={Sizhe Tang and Rongqian Chen and Tian Lan},
      year={2026},
      eprint={2602.02995},
      archivePrefix={arXiv},
      url={https://arxiv.org/abs/2602.02995},
}
```
