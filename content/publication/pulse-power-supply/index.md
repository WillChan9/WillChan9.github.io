---
title: "Stability improvement of pulse power supply with dual-inductance active storage unit using hysteresis current control"
authors:
- Ping Yang
- Xi Chen
- admin
- Yusheng Peng
- Songrong Wu
- Jianping Xu
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "**IEEE Journal on Emerging and Selected Topics in Circuits and Systems (JETCAS)**"
publication_short: "**IEEE Journal on Emerging and Selected Topics in Circuits and Systems (JETCAS)**"

abstract: The output power of the pulsed power supply (PPS) pulsates at the pulse repetition frequency (PRF) of pulse load. The pulsating power will result in a large bus voltage ripple. To balance the instantaneous power difference, a single or dual-inductance active storage unit (ASU) is usually connected in parallel with the output terminal of the PPS. Poor compensating current tracking accuracy of ASU will lead to the output current of PPS suffered from serious current spikes, which affects the stability of the bus voltage. A hysteresis current control (HCC) is proposed to achieve an excellent pulse current compensation performance. Compared with the current mode control (CMC), the small-signal modeling of dual-inductance with HCC is established to illustrate good compensation performance. Besides, a valley voltage loop is introduced to regulate the storage capacitor voltage in dual-inductance ASU to reduce the power loss at any pulse duty cycle. An experimental prototype is built to verify the spikes in output current can be eliminated effectively, the bus voltage keeps smooth and stable, and the output capacitor of the per-stage DC/DC converter is reduced significantly.

# Summary. An optional shortened abstract.
summary: A hysteresis current control (HCC) method is proposed for dual-inductance active storage units (ASUs) to eliminate current spikes, stabilize bus voltage, and reduce power loss in pulsed power supplies.
tags:
- Power Electronics
- Hareware
- Control
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: 'uploads/Stability_Improvement_of_Pulse_Power_Supply_With_Dual-Inductance_Active_Storage_Unit_Using_Hysteresis_Current_Control.pdf'
links:
- name: Link
  url: https://ieeexplore.ieee.org/abstract/document/9312129
url_code: 
url_dataset: ''
url_poster: ''
url_project: '/project/pulse-power/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '' #'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - pulse-power

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

## TL;DR

A **hysteresis current control (HCC)** scheme for dual-inductance active storage units that eliminates output current spikes and keeps the bus voltage smooth and stable in pulsed power supplies.

**Key contributions:**

- A **small-signal model** of the dual-inductance active storage unit under HCC, showing superior compensation performance over conventional current-mode control.
- A **valley-voltage loop** that regulates the storage-capacitor voltage, reducing power loss at any pulse duty cycle.
- Experimental prototype validation: current spikes effectively eliminated, stable bus voltage, and a significantly smaller output capacitor for the per-stage DC/DC converter.

## Learn more

Hardware details are documented on the [project page](/project/pulse-power/).

## BibTeX

```bibtex
@article{yang2021stability,
  title={Stability improvement of pulse power supply with dual-inductance active storage unit using hysteresis current control},
  author={Yang, Ping and Chen, Xi and Chen, Rongqian and Peng, Yusheng and Wu, Songrong and Xu, Jianping},
  journal={IEEE Journal on Emerging and Selected Topics in Circuits and Systems},
  volume={11},
  number={1},
  pages={111--120},
  year={2021},
  publisher={IEEE}
}
```
