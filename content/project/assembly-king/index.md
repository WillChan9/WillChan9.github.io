---
title: 'AR Guiding System: Assembly King'
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

<p><strong>Project report of Assembly King:</strong> 
  <a href="assembly-king.pdf" class="btn-link" target="_blank" rel="noopener noreferrer">PDF</a>
</p>

<p><strong>GitHub repo:</strong> 
  <a href="https://github.com/WillChan9/AssemblyKing_project" class="btn-link" target="_blank" rel="noopener noreferrer">GitHub</a>
</p>

**Demo video of AssemblyKing:**

{{< youtube e0zONt5E8Tk >}}

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

## Project Intro

I developed a AR-Guided Real-Time Tutoring System, "Assembly King", which helps user assemble a 3D-printed mechanism. The application runs on Meta Quest 3 and PC. It aims to facilitate intuitive and real-time interactions between coaches and trainees in application domains such as cooking, scientific experiments, and equipment repair. Please refer to the above documents and code if you are interested in the detailed implementation.

<!-- 
**Project report of Assembly King:**<mark>[AssemblyKing.pdf](assembly-king.pdf)</mark>

**GitHub repo:**<mark>[GitHub](https://github.com/WillChan9/AssemblyKing_project)</mark> -->

This system aims to help trainees do assembly work with real-time reference from the coach. For mechanical part assembly work, due to the massive amount of parts involves in the product and the complexity of the assembly work, people usually need to follow a manual instruction book.

However, such traditional method require professional knowledge because they require users to understand the principles of how parts work together. The limitation of a manual interaction is the way it interacts with users: it shows the parts in 2D and fixed instructions for tutoring without knowing the current situations users might have. This might cause misunderstandings and mistakes in assembly works.

Thus, in our case, we design a real-time tutoring system. Enhanced with expert experience, Vision Language Model, and Computer Vision techniques, AssemblyKing is able to perform accurate and fast-response feedback for users. It can recognize the parts and understand assembly steps, based on user’s current progress, it highlights the parts they need and provide tutoring instructions for users. User can follow coach assembly steps and learn the tasks in a relative short time.

