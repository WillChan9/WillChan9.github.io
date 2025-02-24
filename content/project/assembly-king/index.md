---
title: 'AR project: Assembly King'
summary: A mechanical parts assembly guiding system. 
date: 2024-12-07
type: docs
math: false
tags:
  - AR/VR
  - AI
image:
  caption: 'Assembly King demo on the class'
---

## Project Intro

<div style="text-align: center">
  <a href="your-link">
    <button style="background-color: #a4d61e; margin-top: 6px; margin-bottom: 16px; border-radius: 4px; font-size: 1.6em; padding: 8px 20px;">
      Click Here
    </button>
  </a>
</div>


I developed a AR-Guided Real-Time Tutoring System: Assembly King, the application runs on Meta Quest 3 and PC. AssemblyKing aims
to facilitate intuitive and real-time interactions between coaches and trainees in application domains such as cooking, scientific experiments, and equipment repair. Please refer to the following documents and code if you are interested in the detailed implementation.

**Project report of Assembly King:**<mark>[AssemblyKing.pdf](assembly-king.pdf)</mark>

**GitHub repo:**<mark>[GitHub](https://github.com/WillChan9/AssemblyKing_project)</mark>

This system aims to help trainees do assembly work with real-time reference from the coach. For mechanical part assembly work, due to the massive amount of parts involves in the product and the complexity of the assembly work, people usually need to follow a manual instruction book.

However, such traditional method require professional knowledge because they require users to understand the principles of how parts work together. The limitation of a manual interaction is the way it interacts with users: it shows the parts in 2D and fixed instructions for tutoring without knowing the current situations users might have. This might cause misunderstandings and mistakes in assembly works.

Thus, in our case, we design a real-time tutoring system. Enhanced with expert experience, Vision Language Model, and Computer Vision techniques, AssemblyKing is able to perform accurate and fast-response feedback for users. It can recognize the parts and understand assembly steps, based on user’s current progress, it highlights the parts they need and provide tutoring instructions for users. User can follow coach assembly steps and learn the tasks in a relative short time.

## Video

Here is the demo video of AssemblyKing, which helps user assemble a 3D-printed mechanism:

{{< youtube e0zONt5E8Tk >}}

