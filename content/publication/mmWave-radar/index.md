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
url_project: ''
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
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
