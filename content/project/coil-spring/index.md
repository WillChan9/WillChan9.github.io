---
title: 'Tunable-Stiffness Coil-Spring manipulator'
summary: Design of a pneumatic actuator.
date: 2022-08-01
type: docs
math: false
tags:
  - Soft Robotics
  - Actuator Design
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

<p><strong>ICRA 2023 Paper:</strong> 
  <a href="Design_and_Control_of_a_Tunable-Stiffness_Coiled-Spring_Actuator.pdf" class="btn-link" target="_blank" rel="noopener noreferrer">PDF</a>
</p>

**Demo video of Coil Spring:**

{{< youtube _OzyXiTubnA >}}

Soft robots have many advantages compared to rigid robots, including the ability to deform continuously and compliantly, adapt to unknown situations, and so on. In this research project, we design and build a new kind of manipulator using tunable stiffness springs.

<figure style="text-align: center;">
    <img src="mplmodel.png" width="150" style="display: block; margin: 0 auto;">
    <figcaption>The structure of the multi-segment manipulator</figcaption>
</figure>

The manipulator has several segments, and each segment has several springs. Now suppose the springs in each segment have different stiffness, then each segment would turn in its own direction when the central tendon is pulled down. The system tends to the state of lowest energy at any time, so by constructing the potential energy of the manipulator and solving the optimization problem, we can obtain forward kinematics equations. The following picture is the first version of our manipulator, using stiffness unchangeable TPU springs.

<figure style="text-align: center;">
    <img src="tendon pull down.png" width="700" style="display: block; margin: 0 auto;">
    <figcaption>The multi-segment manipulator with TPU springs</figcaption>
</figure>

For the next prototype, we switch the TPU springs to our new-designed tunable stiffness coil-springs. The coil consists of a ribbon, which is driven by a motor-driven dispenser and stored inside a drum storage. The stiffness is changed by controlling the layers inside the coil. We built a nested ring compression model, and the simulation well-align with the experiment result with measured parameters.

<figure style="text-align: center;">
    <img src="ring model.png" width="500" style="display: block; margin: 0 auto;">
</figure>

<figure style="text-align: center;">
    <img src="Force-displacement curve.png" width="700" style="display: block; margin: 0 auto;">
    <figcaption>Spring model and simulation</figcaption>
</figure>

The actual coil spring prototype and stiffness test for the spring are shown below. The spring is limited to 10 layers due to the friction and motor torque limit. The result shows that it has a high resolution and performs pretty linearly in the first half of compression.

<figure style="text-align: center;">
    <img src="Spring_exploded_view.JPG" width="300" style="display: block; margin: 0 auto;">
    <figcaption>Exploded view of tunable stiffness actuator spring</figcaption>
</figure>

<figure style="text-align: center;">
    <img src="coil_experiment.png" width="300" style="display: block; margin: 0 auto;">
    <figcaption>Experimental stiffness test for single spring</figcaption>
</figure>

We built a 3 DOF single-segment manipulator with 4 springs, a motor-driven tendon connected to the center of the top plate controls the total extension of the manipulator. By tracking center of top plate, we obtained the considerable workspace, and shows a good control accuracy. 

<figure style="text-align: center;">
    <img src="coil_experiment2.png" width="500" style="display: block; margin: 0 auto;">
    <img src="trajectory.png" width="500" style="display: block; margin: 0 auto;">
    <figcaption>Workspace test and trajectory control test for single segment manipulator</figcaption>
</figure>

With this novel spring design, we accurately reach our desired stiffness and control the top plate to follow the goal trajectory. In the future, we will build a multi-segment one with a new control algorithm, so that it can move like a snake!