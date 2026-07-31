---
title: 'Tunable Leg Stiffness in a Monopedal Hopper for Energy-Efficient Vertical Hopping Across Varying Ground Profiles'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jun Kwon
  - Kefan Wu
  - Wei-Hsi Chen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-01-01T00:00:00Z'
# doi: '10.1109/VTC2022-Spring54318.2022.9860614'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "**2025 IEEE International Conference on Robotics and Automation (ICRA)**"
publication_short: "**2025 IEEE International Conference on Robotics and Automation (ICRA)**"

abstract: We present the design and implementation of HASTA (Hopper with Adjustable Stiffness for Terrain Adap- tion), a vertical hopping robot with real-time tunable leg stiffness, aimed at optimizing energy efficiency across various ground profiles (a pair of ground stiffness and damping conditions). By adjusting leg stiffness, we aim to maximize apex hopping height, a key metric for energy-efficient vertical hopping. We hypothesize that softer legs perform better on soft, damped ground by minimizing penetration and energy loss, while stiffer legs excel on hard, less damped ground by reducing limb deformation and energy dissipation. Through experimental tests and simulations, we find the best leg stiffness within our selection for each combination of ground stiffness and damping, enabling the robot to achieve maximum steady- state hopping height with a constant energy input. These results validate our hypothesis and show that tunable stiffness enhances energy-efficient locomotion in dynamic environments. In addition, simulations offer a valuable tool for guiding future controllers in selecting the optimal leg stiffness.

# Summary. An optional shortened abstract.
summary: Some studies show that animals will adjust their leg behavior while in different environments. So in this research, we are aiming to find energy loss reduction strategies by studying how the leg makes contact with the ground.

tags:
  - Legged Robot

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/ICRA2025_HASTA_Robot.pdf'
links:
  - name: arXiv
    url: https://arxiv.org/abs/2508.02873
url_code: 'https://github.com/WillChan9/kodlab_mjbots_sdk'
url_dataset: ''
url_poster: ''
url_project: '/project/hopper-robot/'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=-FwuncAdoNc'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Hopper robot and ground emulator'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - hopper-robot

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

## TL;DR

**HASTA** (Hopper with Adjustable Stiffness for Terrain Adaption) is a vertical hopping robot that tunes its leg stiffness in real time to hop as high as possible on different ground conditions — softer legs win on soft, damped ground; stiffer legs win on hard ground.

**Key contributions:**

- A monopedal hopper with **real-time tunable leg stiffness**, built on pneumatic tunable-stiffness bellows actuators driven by a central tendon.
- A **ground emulator** that physically reproduces pairs of ground stiffness and damping conditions for repeatable locomotion experiments.
- Experiments and simulations identifying the **optimal leg stiffness for each ground profile**, validating that tunable stiffness enhances energy-efficient locomotion in dynamic environments.

## Demo

{{< youtube -FwuncAdoNc >}}

## Learn more

Hardware design, fabrication details, and the electronic system architecture are documented on the [project page](/project/hopper-robot/).

## BibTeX

```bibtex
@misc{chen2025tunablelegstiffnessmonopedal,
  title={Tunable Leg Stiffness in a Monopedal Hopper for Energy-Efficient Vertical Hopping Across Varying Ground Profiles},
  author={Rongqian Chen and Jun Kwon and Kefan Wu and Wei-Hsi Chen},
  year={2025},
  eprint={2508.02873},
  archivePrefix={arXiv},
  primaryClass={cs.RO},
  url={https://arxiv.org/abs/2508.02873},
}
```
