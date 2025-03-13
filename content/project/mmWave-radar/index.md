---
title: 'Tracking algorithm for mmWave radar'
summary: Development of a Target Tracking Algorithm for Automotive mmWave Radar
date: 2021-06-01
type: docs
math: false
tags:
  - Radar Signal Processing
  - Multi-Target Tracking
image:
  caption: ''
---

<style>
  .btn-link {
    display: inline-block;
    background-color: #4da6ff; /* Light blue */
    color: white !important; /* Ensures white text */
    font-size: 1em;
    font-weight: bold;
    padding: 8px 14px;
    border-radius: 6px;
    text-decoration: none;
    transition: background-color 0.2s ease-in-out, text-decoration 0.2s ease-in-out;
  }

  .btn-link:hover {
    background-color: #3399ff; /* Darker blue on hover */
    color: white !important; /* Prevents green color */
    text-decoration: underline;
  }

  .center {
  display: block;
  margin-left: auto;
  margin-right: auto;
}

</style>

<p><strong>VTC 2022 Paper:</strong> 
  <a href="mmwave_paper.pdf" class="btn-link" target="_blank" rel="noopener noreferrer">PDF</a>
</p>
<p><strong>My Undergraduate Theis (本科毕业论文):</strong> 
  <a href="undergrad_thesis.pdf" class="btn-link" target="_blank" rel="noopener noreferrer">PDF</a>
</p>

As part of my undergraduate thesis project, I developed a target tracking algorithm for automotive millimeter-wave (mmWave) radar, specifically utilizing Texas Instruments’ AWR1642 sensor. Due to the low resolution of radar images, classifying objects remains challenging. To improve target distinguishability, I implemented a clustering-based approach that groups individual radar detection points into meaningful clusters, allowing for the extraction of richer features such as shape, area, and density.

<figure style="text-align: center;">
    <img src="radar.jpg" width="400" style="display: block; margin: 0 auto;">
    <figcaption>Automotive radar sensor AWR1642 from Texas Instrument</figcaption>
</figure>

Instead of relying on individual points with limited information, the algorithm aggregates similar points into clusters, leveraging spatial and motion-based characteristics. The clustering process is enhanced by incorporating additional criteria, such as velocity and amplitude, to improve accuracy and reduce false detections.

<figure style="text-align: center;">
    <img src="figure2.PNG" width="600" style="display: block; margin: 0 auto;">
    <figcaption>Clustering Algorithm</figcaption>
</figure>

For data association, I designed a similarity function to match clusters across frames based on multiple features, including distance, velocity, area, overlapping regions, and amplitude. This approach ensures robust cluster tracking, even in noisy environments. The system then applies a Kalman filter to refine trajectory estimates, ensuring smooth and accurate tracking of moving objects.

The algorithm was tested in various automotive scenarios, demonstrating improved object tracking accuracy and trajectory prediction. The results validate the effectiveness of the proposed clustering and data association methods in enhancing radar-based target tracking for autonomous driving applications.

<figure style="text-align: center;">
    <img src="figure12(a).png" width="400" style="display: block; margin: 0 auto;">
    <figcaption>Test scenario</figcaption>
</figure>

<div style="display: flex; justify-content: center; gap: 20px;">
    <figure style="text-align: center;">
        <img src="radarmap1.png" width="200">
    </figure>
    <figure style="text-align: center;">
        <img src="radarmap2.png" width="200">
    </figure>
    <figure style="text-align: center;">
        <img src="radarmap3.png" width="200">
    </figure>
    <figure style="text-align: center;">
        <img src="radarmap4.png" width="200">
    </figure>
</div>

<div style="display: flex; justify-content: center; gap: 20px;">
    <figure style="text-align: center;">
        <img src="clustermap1.png" width="200">
    </figure>
    <figure style="text-align: center;">
        <img src="clustermap2.png" width="200">
    </figure>
    <figure style="text-align: center;">
        <img src="clustermap3.png" width="200">
    </figure>
    <figure style="text-align: center;">
        <img src="clustermap4.png" width="200">
    </figure>
    
</div>

<figure style="text-align: center;">
    <img src="tracks.png" width="400" style="display: block; margin: 0 auto;">
    <figcaption>The tracking result</figcaption>
</figure>