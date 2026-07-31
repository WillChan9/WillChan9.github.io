---
title: 'Design and Control of a Tunable-Stiffness Coiled-Spring Actuator'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shivangi Misra
  - Mason Mitchell
  - admin
  - Cynthia Sung

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-08-30T00:00:00Z'
# doi: '10.1109/VTC2022-Spring54318.2022.9860614'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "**2023 IEEE International Conference on Robotics and Automation (ICRA)**"
publication_short: "**2023 IEEE International Conference on Robotics and Automation (ICRA)**"

abstract: We propose a novel design for a lightweight and compact tunable stiffness actuator capable of stiffness changes up to 20x. The design is based on the concept of a coiled spring, where changes in the number of layers in the spring change the bulk stiffness in a near linear fashion. We present an elastica nested rings model for the deformation of the proposed actuator and empirically verify that the designed stiffness-changing spring abides by this model. Using the resulting model, we design a physical prototype of the tunable-stiffness coiled-spring actuator and discuss the effect of design choices on the resulting achievable stiffness range and resolution. In the future, this actuator design could be useful in a wide variety of soft robotics applications, where fast, controllable, and local stiffness change is required over a large range of stiffnesses.

# Summary. An optional shortened abstract.
summary: Soft robots have many advantages compared to rigid robots, including the ability to deform continuously and compliantly, adapt to unknown situations, and so on. In this research project, we design and build a new kind of manipulator using tunable stiffness springs.

tags:
  - Soft Robotics
  - Actuator Design
  - Computational Design

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/Design_and_Control_of_a_Tunable-Stiffness_Coiled-Spring_Actuator.pdf'
links:
- name: Link
  url: https://ieeexplore.ieee.org/document/10161218
url_code: ''
url_dataset: ''
url_poster: ''
url_project: '/project/coil-spring/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - coil-spring

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

## TL;DR

A lightweight, compact actuator that changes stiffness by **up to 20×** using a coiled spring: changing the number of layers in the coil changes the bulk stiffness in a near-linear fashion.

**Key contributions:**

- An **elastica nested-rings model** of the actuator's deformation, empirically verified on the fabricated spring.
- A physical prototype with design guidance on the achievable **stiffness range and resolution**.
- A building block for soft robots that need fast, controllable, local stiffness change over a large range.

## Learn more

Design details and hardware are documented on the [project page](/project/coil-spring/).

## BibTeX

```bibtex
@inproceedings{misra2023design,
  title={Design and control of a tunable-stiffness coiled-spring actuator},
  author={Misra, Shivangi and Mitchell, Mason and Chen, Rongqian and Sung, Cynthia},
  booktitle={2023 IEEE International Conference on Robotics and Automation (ICRA)},
  pages={634--640},
  year={2023},
  organization={IEEE}
}
```
