---
title: 'Legged Hopping Robot and Ground Emulator'
summary: HASTA, Hopper with Adjustable Stiffness for Terrain Adaption. Underneath it is a ground emulator.
date: 2024-05-01
type: docs
math: false
tags:
  - Legged Robot
  - Locomotion
image:
  caption: ''
---

<p><strong>ICRA 2025 Accepted Paper:</strong> 
  <a href="ICRA2025_HASTA_Robot.pdf" class="btn-link" target="_blank" rel="noopener noreferrer">PDF</a>
</p>

<p><strong>My Master Thesis:</strong> 
  <a href="master_thesis.pdf" class="btn-link" target="_blank" rel="noopener noreferrer">PDF</a>
</p>

<p><strong>GitHub repo:</strong> 
  <a href="https://github.com/WillChan9/kodlab_mjbots_sdk" class="btn-link" target="_blank" rel="noopener noreferrer">GitHub</a>
</p>

**Demo video of HASTA project:**

{{< youtube -FwuncAdoNc >}}

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
</style>

Legged robots are inspired by natural creatures, which offers unique advantages over wheeled robots in complex environments. Some studies show that animals will adjust their leg behavior while in different environments. So in this research, we are aiming to find energy loss reduction strategies by studying how the leg makes contact with the ground.

So in this study, we built a monopedal legged hopper robot and ground emulator, modeled the leg and hopper behavior, and characterized them with experiments. We also proposed a ground adaptation strategy for saving energy during the stance phase, based on the stiffness and damping coefficient of the system.

<div style="display: flex; justify-content: center; align-items: flex-end; gap: 10px;">
    <img src="hopper_running.gif" width="200">
    <img src="hopper_running2.gif" width="300">
</div>

The gif above demonstrate the functionality of the hopper and the ground emulator. The ground emulator has the capability to adjust its platform's stiffness and damping. Meanwhile, the hopper's leg can modify its stiffness using pneumatic tunable-stiffness bellows actuators, powered by a central tendon which is managed by a brushless motor.

Through simulations, it's observed that by adjusting the leg stiffness, the hopper can minimize energy use for particular ground conditions. Hence, it's crucial to develop a mathematical model to grasp the impact of various hopper parameters on its dynamic behaviors. For sustained hopping on the surface, the hopper has to replenish energy to offset the energy lost due to damping. In this process, the hopper pre-compresses its leg mid-air and releases it upon detecting ground contact. With consistent pre-compression, the hopping height converges and its dynamic state converges to a limit cycle, as depicted in the subsequent illustration.

<figure style="text-align: center;">
    <img src="new_model.gif">
    <figcaption>The hopper state will converge to a limit cycle in the phase portrait</figcaption>
</figure>

In our prototyping phase, our team dedicated a significant amount of time to the design and development of the mechanical structure, electrical framework, and software system. We employed a diverse array of fabrication techniques to construct the prototype, such as molding, 3D printing, laser cutting, turning, and milling. We also opted for varied materials to suit different components. For instance, silicone rubber was used for the actuator, nylon for the guide rods, wood for the base plates, aluminum for motor standoffs, carbon fiber for the pulley systems, and Ultra-High Molecular Weight Polyethylene (UHMWPE) for the central tendon. This strategic selection of materials ensured that our system was not only efficient and durable but also lightweight and sturdy. For a deeper dive into the design specifics, please refer my master's thesis or our ICRA papers.

<figure style="text-align: center;">
    <img src="hopper CAD.png">
    <figcaption>Hopper mechanism overview</figcaption>
</figure>

The hardware and software components represent a significant portion of our work. Our system comprises four microcontrollers, with each responsible for a distinct role:

- Raspberry Pi 3B+ acts as the primary controller, undertaking most of the mathematical computations.

- Arduino Nano is utilized for actuator stiffness control, specifically chosen for its abundance of external interrupt pins.

- ESP32 monitors the system's power usage and communicates this data to the user via Bluetooth.

- Raspberry Pi Pico gauges the hopper toe force and the pressure within the leg bellows. We also envision deploying machine learning models on this microcontroller in the future.

<figure style="text-align: center;">
    <img src="infra.png">
    <figcaption>Hopper electronic system overview</figcaption>
</figure>