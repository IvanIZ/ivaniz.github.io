---
layout: post_index
categories: media
title: ""

---

For a complete list of my publications, please visit my [Google Scholar](https://scholar.google.ca/citations?user=8zyHdjoAAAAJ&hl=en&oi=ao).


## Occupancy Prediction for Autonomous Surface Vehicle Navigation in Ice-Covered Water
<img style="float: right; padding-left:20px;" src="/assets/sim_img.jpg" width="340" height="260">

Autonomous navigation in ice-covered waters poses significant challenges due to the frequent lack of viable collision-free trajectories. When complete obstacle avoidance is infeasible, it becomes imperative for the navigation strategy to minimize collisions. Additionally, the dynamic nature of ice, which moves in response to ship maneuvers, complicates the path planning process. To address these challenges, we propose a novel deep learning model to estimate the coarse dynamics of ice movements triggered by ship actions through occupancy estimation. To ensure real-time applicability, we propose a novel approach that caches intermediate prediction results and seamlessly integrates the predictive model into a graph search planner. We evaluate the proposed planner in both simulation and in a physical testbed against existing approaches and show that our planner exhibits superior performance in collision reduction. 

Under Review ICRA 2025 [[paper](https://ieeexplore.ieee.org/abstract/document/10400830)][[Github](https://drive.google.com/file/d/1FZqU1ECDhD2d93hmC90mmE7PjuCymzC-/view?usp=sharing)]


## Attentiveness Map Estimation for Haptic Teleoperation of Mobile Robot Obstacle Avoidance and Approach
<img style="float: right; padding-left:20px;" src="/assets/real_world_prelim_v4.png" width="300" height="390">

Haptic feedback can improve safety of teleoperated robots when situational awareness is limited or operators are inattentive. Standard potential field approaches increase haptic resistance as an obstacle is approached, which is desirable when the operator is unaware of the obstacle but undesirable when the movement is intentional, such as when the operator wishes to inspect or manipulate an object. This paper presents a novel haptic teleoperation framework that estimates the operator's attentiveness to obstacles and dampens haptic feedback for intentional movement. A biologically-inspired attention model is developed based on computational working memory theories to integrate visual saliency estimation with spatial mapping. The attentiveness map is generated in real-time, and our system renders lower haptic forces for obstacles that the operator is estimated to be aware of. Experimental results in simulation show that the proposed framework outperforms haptic teleoperation without attentiveness estimation in terms of task performance, robot safety, and user experience.

RA-L 2024 [[paper](https://ieeexplore.ieee.org/abstract/document/10400830)]



