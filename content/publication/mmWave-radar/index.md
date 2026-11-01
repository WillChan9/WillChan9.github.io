---
title: 'A Cluster-Based Weighted Feature Similarity Moving Target Tracking Algorithm for Automotive FMCW Radar'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yingquan Zou
  - Anyong Gao
  - Leshi Chen

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-07-01T00:00:00Z'
# doi: '10.1109/VTC2022-Spring54318.2022.9860614'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "**2022-Spring IEEE Vehicular Technology Conference (VTC)**"
publication_short: "**2022-Spring IEEE Vehicular Technology Conference (VTC)**"

abstract: We studied a target tracking algorithm based on millimeter-wave (MMW) radar in an autonomous driving environment. Aiming at the cluster matching in the target tracking stage, a new weighted feature similarity algorithm is proposed, which increases the matching rate of the same target in adjacent frames under strong environmental noise and multiple interference targets. For autonomous driving scenarios, we constructed a method that uses its motion parameters to extract and correct the trajectory of a moving target, which solves the problem of moving target detection and trajectory correction during vehicle movement. Finally, the feasibility of the proposed method was verified by a series of experiments in autonomous driving environments. The results verify the high recognition accuracy and low positional error of the method.

# Summary. An optional shortened abstract.
summary: We developed a target tracking algorithm for automotive mmWave radar. Due to radar image low resolution, it’s hard to classify objects by data points.  To make the targets more distinguishable, our algorithm merges the points into a bigger cluster, extract features for later classification and tracking tasks. 

tags:
  - mmWave Radar
  - Object Tracking

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'uploads/A_Cluster_Based_Weighted_Feature_Similarity_Moving_Target_Tracking_Algorithm_for_Automotive_FMCW_Radar.pdf'
links:
- name: Link
  url: https://ieeexplore.ieee.org/abstract/document/9860614
url_code: ''
url_dataset: ''
url_poster: ''
url_project: '/project/mmwave-radar/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Automotive mmWave radar TI AWR1642'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - mmWave-radar

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

## TL;DR

A moving-target tracking algorithm for automotive FMCW mmWave radar: sparse radar points are merged into clusters and matched across frames by **weighted feature similarity**, staying robust under strong environmental noise and multiple interfering targets.

**Key contributions:**

- A **cluster-based weighted feature similarity** matching algorithm that raises the same-target matching rate across adjacent frames.
- **Trajectory extraction and correction** for moving targets using the ego vehicle's motion parameters.
- Verified in autonomous-driving experiments with high recognition accuracy and low positional error.

## Learn more

Implementation details are documented on the [project page](/project/mmwave-radar/).

## BibTeX

```bibtex
@inproceedings{chen2022cluster,
  title={A Cluster-Based Weighted Feature Similarity Moving Target Tracking Algorithm for Automotive FMCW Radar},
  author={Chen, Rongqian and Zou, Yingquan and Gao, Anyong and Chen, Leshi},
  booktitle={2022 IEEE 95th Vehicular Technology Conference:(VTC2022-Spring)},
  pages={1--5},
  year={2022},
  organization={IEEE}
}
```
