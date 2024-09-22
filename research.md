---
layout: post_index
categories: media
title: ""

---

For the complete list of publications, please visit my [Google Scholar](https://scholar.google.ca/citations?user=8zyHdjoAAAAJ&hl=en&oi=ao) profile.


## Autonomous Navigation in Ice-Covered Waters with Learned Predictions on Ship-Ice Interactions
<img style="float: right; padding-left:20px;" src="/assets/method_video.gif" width="400" height="225">

Autonomous navigation in ice-covered waters poses significant challenges due to the frequent lack of viable collision-free trajectories. When complete obstacle avoidance is infeasible, it becomes imperative for the navigation strategy to minimize collisions. Additionally, the dynamic nature of ice, which moves in response to ship maneuvers, complicates the path planning process. To address these challenges, we propose a novel deep learning model to estimate the coarse dynamics of ice movements triggered by ship actions through occupancy estimation. To ensure real-time applicability, we propose a novel approach that caches intermediate prediction results and seamlessly integrates the predictive model into a graph search planner. We evaluate the proposed planner in both simulation and in a physical testbed against existing approaches and show that our planner exhibits superior performance in collision reduction. 

Under Review ICRA 2025 <br>
[[Paper](https://arxiv.org/pdf/2409.11326)][[Project Page](https://sites.google.com/view/predictive-asv-nav/)][[Github](https://github.com/IvanIZ/predictive-asv-planner)]
<br>
<p style="margin-top: 40px;"></p>
---

## Attentiveness Map Estimation for Haptic Teleoperation of Mobile Robot Obstacle Avoidance and Approach
<img style="float: right; padding-left:20px;" src="/assets/real_world_prelim_v4.png" width="300" height="390">

Haptic feedback can improve safety of teleoperated robots when situational awareness is limited or operators are inattentive. Standard potential field approaches increase haptic resistance as an obstacle is approached, which is desirable when the operator is unaware of the obstacle but undesirable when the movement is intentional, such as when the operator wishes to inspect or manipulate an object. This paper presents a novel haptic teleoperation framework that estimates the operator's attentiveness to obstacles and dampens haptic feedback for intentional movement. A biologically-inspired attention model is developed based on computational working memory theories to integrate visual saliency estimation with spatial mapping. The attentiveness map is generated in real-time, and our system renders lower haptic forces for obstacles that the operator is estimated to be aware of. Experimental results in simulation show that the proposed framework outperforms haptic teleoperation without attentiveness estimation in terms of task performance, robot safety, and user experience.

RA-L 2024 <br> 
[[Paper](https://ieeexplore.ieee.org/abstract/document/10400830)][[Demo Video](https://drive.google.com/file/d/107Mi25OYJLrMjxFr7Zrt1dxcU89oRw4U/view?usp=drive_link)]
<br>
<p style="margin-top: 40px;"></p>
---

## Hierarchical Intention Tracking for Robust Human-Robot Collaboration in Industrial Assembly Tasks
<img style="float: right; padding-left:20px;" src="/assets/hit_project/hit_visual.png" width="300" height="285">

Collaborative robots require effective human intention estimation to safely and smoothly work with humans in less structured tasks such as industrial assembly, where human intention continuously changes. We propose the concept of intention tracking and introduce a collaborative robot system that concurrently tracks intentions at hierarchical levels. The high-level intention is tracked to estimate human's interaction pattern and enable robot to (1) avoid collision with human to minimize interruption and (2) assist human to correct failure. The low-level intention estimate provides robot with task-related information. We implement the system on a UR5e robot and demonstrate robust, seamless and ergonomic human-robot collaboration in an ablative pilot study of an assembly use case.

ICRA 2023 <br> 
[[Paper](https://ieeexplore.ieee.org/abstract/document/10160515)][[Project Page](https://sites.google.com/view/hierarchicalintentiontracking)]
