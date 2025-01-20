---
layout: page
permalink: /Research/
title: Research
description: An overview of the research conducted in my lab. 
nav: true
nav_order: 2
---
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-HLN7KFZYDV"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-HLN7KFZYDV');
</script>

## Marine Robotics

<div class="row align-items-center">
    <div class="col-4">
      {% include figure.html path="assets/img/underwater.jpg" title="your image title" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-8" style="text-align: justify;">
      We develop algorithms for robust autonomous operation in challenging underwater environments, focusing on the unique challenges of the marine environment, such as the limited communication, dynamic disturbances, and degraded sensing. Research questions include: how to achieve reliable localization with limited acoustic sensing; how to enable efficient multi-robot coordination under severe constraints; and how to perform robust perception and mapping in visually degraded conditions. Our work spans fundamental robotics capabilities from SLAM to motion planning and control, with particular emphasis on field deployment and validation.
    </div>
</div>



Recent publications:   
[FRAGG-Map: Frustum Accelerated GPU-Based Grid Map](https://ieeexplore.ieee.org/abstract/document/10801590)  
[Digital Twins Below the Surface: Enhancing Underwater Teleoperation](https://arxiv.org/abs/2402.07556)  

## Reinforcement Learning


<div class="row align-items-center">
    <div class="col-4">
      {% include figure.html path="assets/img/publication_preview/adaptive_mimo.jpg" title="your image title" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-8">
      Our research focuses on developing robust reinforcement learning algorithms that can handle the challenges of real-world robotics: continuous action spaces, partial observability, and safety constraints. We investigate how to enable efficient learning from limited data, how to incorporate safety constraints into the learning process, and how to transfer learned policies across different robots and tasks. A key focus is bridging the gap between simulation and reality through techniques like domain randomization and meta-learning.
    </div>
</div>

Recent publications:  
[MarineGym: Accelerated Training for Underwater Vehicles with High-Fidelity RL Simulation](https://arxiv.org/abs/2410.14117)  
[Harnessing traditional controllers for fast-track training of deep reinforcement learning control strategies](https://www.tandfonline.com/doi/full/10.1080/20464177.2024.2367276)  

## Multi-agent Systems

<div class="row align-items-center">
    <div class="col-4">
      {% include figure.html path="assets/img/multiagent.png" title="your image title" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-8">
      Our research explores the design of control and planning strategies for multi-robot teams working in real-world environment. We are particularly interested in machine learning techniques, such as reinforcement learning, to achieve distributed decision-making and efficient coordination. We investigate areas such as cooperative control, multi-agent coordination, ad hoc teamwork, and the deployment on these techniques in real world robots. By transforming how robotic tasks are approached, our focus on distributed autonomy and cooperative behavior enables the deployment of larger-scale and more robust robotic systems across a range of application domains.
    </div>
</div>


Recent publications:  
[Learning Complex Teamwork Tasks Using a Given Sub-task Decomposition](https://www.ifaamas.org/Proceedings/aamas2024/pdfs/p598.pdf)   
[A General Learning Framework for Open Ad Hoc Teamwork Using Graph-based Policy Learning](https://www.jmlr.org/papers/v24/22-099.html)