---
permalink: /
title: "Chen's Place"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a first-year PhD student at the University of Colorado Boulder, advised by <a href="https://www.colorado.edu/cs/nikolaus-correll" style="text-decoration:none">Prof. Nikolaus Correll</a> and <a href="https://www.colorado.edu/cs/alessandro-roncone" style="text-decoration:none">Prof. Alessandro Roncone</a>.

My research goal is to build intelligent agents that can efficiently learn to understand our world and interact with humans. 
To this end, my work bridges two critical areas: 1) *Agent Learning*: Improving the generalization and sample-efficiency of reinforcement learning for robotic tasks like visual navigation and manipulation. 2) *Foundational Models*: Scaling the inference of pre-trained models (e.g., large language model or vision language action model) that can serve as the knowledge backbone for these agents.

Previously, I worked 2 years as a Research Engineer at Chinese Academy of Sciences, supervised by <a href="https://scholar.google.com/citations?user=nD0I3PUAAAAJ&hl=en" style="text-decoration:none">Prof. Jiafeng Guo</a>. I earned my M.S. in Computer Science from the University of Southern California, where I was advised by <a href="http://ilab.usc.edu/itti/" style="text-decoration:none">Prof. Laurent Itti</a>.

You can find my CV here: <a href="../assets/Chen_Liu_Resume.pdf" style="text-decoration:none">Chen's Curriculum Vitae</a>.

Research
========
<img  style="margin-top:4em;" align="left" src="../images/carlagstview.png" width="160" height="160"/> 
<td>
    <a href="https://arxiv.org/abs/2310.18847"><p style="margin-left:10em;">
        Bird’s Eye View Based Pretrained World model for Visual Navigation  <br></a>
    Kiran Lekkala*, <strong>Chen Liu*</strong>, Laurent Itti <br>
    <em> Published at International Symposium on Robotics Research (ISRR), December, 2024; Also presented at NeurIPS 2023 Robot Learning Workshop. </em> <br>
    We propose a robust system that integrates the control policy with pretrained visual perception model and LSTM-based robustness-enhanced world model, facilitating seamless application of the policy in real-world scenarios.</p>
</td>

<img  style="margin-top:4em;" align="left" src="../images/uscilab3d.gif" width="160" height="160"/> 
<td>
    <a href="https://klekkala.github.io/files/uscilab3d.pdf"> <p style="margin-left:10em;">
        USCILab3D Dataset: A Large-scale, Long-term, Semantic, Outdoor 3D Dataset<br></a> 
    Kiran Lekkala*, Henghui Bao*, Piexu Cai, Kevin Lim, <strong>Chen Liu</strong>, Laurent Itti <br>
    <em> Published at Neural Information Processing Systems (NeurIPS), December, 2024; Accepted into the Open X-Embodiment Collaboration </em> <br>
    We propose a novel pipeline that uses foundational models to annotate 3D pointclouds. We also release a 3D dataset, consisting of images and pointclouds, that is collected over the span of an year on a large campus-scale environment.</p>
</td>

<img  style="margin-top:1em;" align="left" src="../images/chrome-capture-2023-9-20.gif" width="160" height="160"/> 
<td>
    <p style="margin-left:10em;">
        Facilitating Diverse Manipulation with Vision-Language Model<br>
    <em> preprint </em> <br>
    <strong>Chen Liu</strong>, Sumedh Sontakke, Laurent Itti <br>
    We introduce a multi-task robotic system that empowers robots to perform long-horizon manipulation tasks by mimicking a human demonstration video.</p>
</td>

Selected Projects
========
<img  style="margin-top:1em;" align="left" src="../images/framework.png" width="160" height="160"/> 
<td>
  <p style="margin-left:10em;">
    <a href="https://github.com/gomate-community/TrustRAG" style="text-decoration:none">
        TrustRAG：The RAG Framework within Reliable input,Trusted output<br>
    </a>
    TrustRAG is a configurable and modular Retrieval-Augmented Generation (RAG) framework designed to provide reliable input and trusted output, ensuring users can obtain high-quality and trustworthy results in retrieval-based question-answering scenarios.</p>
</td>
<img  style="margin-top:1em;" align="left" src="../images/scoomatic.png" width="160" height="160"/> 
<td>
  <p style="margin-left:10em;">
    <a href="https://github.com/crellian/Schoomatic" style="text-decoration:none">
        Schoomatic - A Differential-Drive Robot Simulator<br>
    </a>
    I develop a robot simulator built on CARLA and Unreal Engine 4, embracing features such as NPC traffic, variable weather conditions and global waypoint planning. Additionally, our codebase provides integration with <a href="https://github.com/crellian/schoomatic_visnav" style="text-decoration:none">RLLib</a> reinforcement learning framework and <a href="https://github.com/crellian/Schoomatic-Autopilot" style="text-decoration:none"> ROS </a> environments.</p>
</td>
<img  style="margin-top:0em;" align="left" src="../images/autopilot.png" width="160" height="160"/> 
<td>
  <p style="margin-left:10em;">
    <a href="https://github.com/crellian/Schoomatic-Autopilot" style="text-decoration:none">
        Schoomatic Autopilot<br>
    </a>
    I implement a ROS-based end-to-end robot navigation system including A* global path planning, Gmapping SLAM, LiDAR-based occupancy grid mapping, Timed-Elastic-Band obstacle avoidance, and PD motion control.</p>
</td>
<img  style="margin-top:2em;" align="left" src="../images/multi-tasks.png" width="160" height="160"/> 
<td>
  <p style="margin-left:10em;">
    <a href="../assets/weather.pdf" style="text-decoration:none">
        Deep Learning-based Image Bad Weather Removal<br>
    </a>
    We improve the state-of-the-art transformer-based model, TransWeather, to restore images degraded by different bad weathers. We Implement and compare CBMA, LeFF, Coordinate Attention and Global-Enhanced Transformer to
adapt the model to heavy rain scenarios. We also design a cascaded model to improve the restoration performance</p>
</td>
<img  style="margin-top:0em;" align="left" src="../images/Lenna.png" width="160" height="160"/> 
<td>
  <p style="margin-left:10em;">
    <a href="https://github.com/crellian/CVLab" style="text-decoration:none">
        CVLab<br>
    </a>
    I build a computer vision library including features such as: a template Matrix class with reference counting, matrix operations, image filters (linear, nonlinear, morphological, and Gabor), image pyramids, etc.</p>
</td>


Experience
========
<img  style="margin-top:0em;" align="left" src="../images/logo.png" width="160" height="160"/>
<td>
  <p style="margin-left:10em;">
    <a href="https://gomall.xir.cn/#/home/project" style="text-decoration:none">
        XIR <br>
    </a>    
   <strong>Research Engineer at Chinese Academy of Sciences, 2023 - 2025</strong><br>
I co-led the architecture and development of a comprehensive LLMOps platform to streamline the end-to-end model lifecycle, from training to production. For inference, I engineered an auto-scaling deployment system built on Kubernetes, integrating vLLM for optimized performance and Ray for distributed orchestration. This system ensured high availability and low-latency responses for production models. On the training side, I developed a robust, distributed training platform using DeepSpeed to handle massive-scale models, and also deployed a multi-modal training system using LlamaFactory, which enabled users to fine-tune models easily.</p>
</td>

Invited Talks
========
University of Electronic Science and Technology of China (UESTC),<br>
Shenzhen Technology University (SZTU),<br>
University of Chinese Academy of Sciences (UCAS)
