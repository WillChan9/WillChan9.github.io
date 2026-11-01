---
title: 'From Description to Interactive VR Scene: An LLM Agent for Authoring Immersive Experiences'

authors:
  - admin
  - Allison Andreyev
  - Xuan Wang
  - Jianan Jiang
  - Bin Li
  - Tian Lan

date: '2026-10-01T00:00:00Z'

publishDate: '2026-10-01T00:00:00Z'

publication_types: ['paper-conference']

publication: "**2026 IEEE Visualization Conference (IEEE VIS) Workshop on Visualization and Generative AI (VIS × GenAI) (Accepted)**"
publication_short: "**2026 IEEE Visualization Conference (IEEE VIS) Workshop on Visualization and Generative AI (VIS × GenAI) (Accepted)**"

abstract: 'Authoring interactive immersive scenes for healthcare training and patient education today requires sustained collaboration between developers, 3D-modeling artists, and clinicians, putting immersive medical visualization out of reach for most domain experts. We present an LLM-based multi-module agent that turns a single natural-language description into a fully populated, interactive VR scene, lowering the authoring barrier from code and 3D tooling to natural language commands. A closed loop between a Python reasoning core and a Unity runtime combines a frontier-LLM planner with lightweight VLM critics grounded in three orthogonal screenshots. A separate interaction layer compiles affordances and story logic into a JSON so runtime response is LLM-free. Across fifteen diverse healthcare scenarios (45 trials), the agent recovers the correct object set in every scene at 5.1 frontier-LLM calls and 113 s per trial, and generates coherent multi-beat story lines averaging 5.0 beats per scenario.'

summary: 'An LLM-based multi-module agent that turns a single natural-language description into a fully populated, interactive healthcare VR scene in Unity, with a frontier-LLM planner, lightweight VLM critics, and an LLM-free runtime interaction layer.'

tags:
  - LLM Agents
  - Virtual Reality
  - Healthcare
  - Procedural Generation

featured: false

url_pdf: 'uploads/From_Description_to_Interactive_VR_Scene_An_LLM_Agent_for_Authoring_Immersive_Experiences.pdf'
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

Describe a healthcare training experience in plain English (for example, "generate an operation room with instruments and surgeons"), and the agent builds the **entire interactive VR scene** in Unity: objects, layout, characters, per-object interactions, and a sequential story line.

<figure>
  <img src="overview.png" alt="Environment generation pipeline" />
  <figcaption>Environment generation pipeline: Parser, Context, Multi-Thread Reflection, and Decision modules in a closed loop with the Unity runtime</figcaption>
</figure>

**Key contributions:**

- A **multi-module agent architecture** (Parser, Context, Multi-Thread Reflection, Decision, Unity Operation) that lowers the authoring barrier for immersive medical visualization from code and 3D tooling to natural language.
- A **two-tier LLM design**: a frontier LLM handles a few high-leverage calls (scene synthesis, interaction map, story line), while lightweight VLM critics paired with deterministic checkers (Bound, Collision, Physics, Semantic, Characters) close the reflection loop over **three orthogonal screenshots**.
- An **LLM-free interaction layer**: an interaction map of per-object affordances and a strictly sequential story line are compiled to JSON up front, so runtime responses need no further LLM calls.
- Evaluated on **15 specialty-diverse healthcare-VR scenarios** (45 trials): the correct object set is recovered in every scene at **5.1 frontier-LLM calls** and **113 s** per trial, with story lines averaging **5.0 beats**.

## BibTeX

```bibtex
@inproceedings{chen2026description,
  title={From Description to Interactive VR Scene: An LLM Agent for Authoring Immersive Experiences},
  author={Chen, Rongqian and Andreyev, Allison and Wang, Xuan and Jiang, Jianan and Li, Bin and Lan, Tian},
  booktitle={IEEE VIS 2026 Workshop on Visualization and Generative AI (VIS x GenAI)},
  year={2026}
}
```
