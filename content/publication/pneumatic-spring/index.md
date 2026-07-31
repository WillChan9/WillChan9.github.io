---
title: 'Design and Characterization of a Pneumatic Tunable-Stiffness Bellows Actuator'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Jun Kwon
  - Wei-Hsi Chen
  - Cynthia Sung

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-02-01T00:00:00Z'
# doi: '10.1109/VTC2022-Spring54318.2022.9860614'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-13T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "**2024 IEEE International Conference on Soft Robotics (RoboSoft)**"
publication_short: "**2024 IEEE International Conference on Soft Robotics (RoboSoft)**"

abstract: We introduce a self-contained pneumatic actuator capable of 1.43 times stiffness gain from 1332 N/m to 1913 N/m without needing an external air source or valve. The design incorporates an air chamber bellows and a spring bellows, connected and sealed. Stiffness modulation is achieved by altering the air chamber volume. We present an approach for computing the volume, pressurized force, and stiffness of a single bellows component, as well as methods for composing single bellows models to predict the change in stiffness of the dual bellows actuator as a function of air chamber compression. We detail the fabrication of the actuator and verify the models on the fabricated prototype. This actuator holds promise for future integration in tunable stiffness robots demanding high strength and adaptability in dynamic scenarios.

# Summary. An optional shortened abstract.
summary: we are aiming to build a pneumatic actuator that is free of air compress source and valves. We are also trying to find an precise model to characterize its output including position, volume, pressure and force.

tags:
  - Soft Robotics
  - Actuator Design
  - Computational Design

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/pneumatic_actuator.pdf'
links:
- name: Link
  url: https://ieeexplore.ieee.org/document/10521916
url_code: ''
url_dataset: ''
url_poster: ''
url_project: '/project/bellows/'
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
  - bellows

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

## TL;DR

A **self-contained** pneumatic actuator that achieves a **1.43×** stiffness gain (1332 → 1913 N/m) with **no external air source or valves**: an air-chamber bellows and a spring bellows are connected and sealed, and compressing the air chamber modulates the stiffness.

**Key contributions:**

- Analytical models for the **volume, pressurized force, and stiffness** of a single bellows, composed to predict the stiffness change of the dual-bellows actuator.
- Detailed **fabrication process** and model verification on the physical prototype.
- A tunable-stiffness building block for robots demanding strength and adaptability — it later became the leg of our [HASTA hopping robot](/publication/hopper-robot/).

## Learn more

Design and fabrication details are documented on the [project page](/project/bellows/).

## BibTeX

```bibtex
@inproceedings{chen2024design,
  title={Design and Characterization of a Pneumatic Tunable-Stiffness Bellows Actuator},
  author={Chen, Rongqian and Kwon, Jun and Chen, Wei-Hsi and Sung, Cynthia},
  booktitle={2024 IEEE 7th International Conference on Soft Robotics (RoboSoft)},
  pages={997--1003},
  year={2024},
  organization={IEEE}
}
```
