---
layout: post_index
categories: media
title: ""

---

For the complete list of publications, please visit my [Google Scholar](https://scholar.google.ca/citations?user=8zyHdjoAAAAJ&hl=en&oi=ao) profile.


## Diffusion Planning for Non-Prehensile Navigation Among Movable Obstacles
<img style="float: right; padding-left:20px;" src="/assets/diffusion_visual2.png" width="300" height="298">

Mobile robots are frequently tasked with navigating in cluttered environments where obstacles are movable, leading to Navigation Among Movable Obstacles (NAMO). Prior NAMO methods often rely on manipulators to remove obstacles from the planned path. However, manipulators are not feasible for all robots due to cost considerations, structural and task constraints. This work addresses this gap by exploring non-prehensile NAMO, where the robot interacts with obstacles using non-grasping actions such as pushing. We study diverse non-prehensile NAMO tasks, including goal-directed navigation (e.g., autonomous navigation in icy waters), pushing tasks for object deliveries and arrangements, and area-clearing operations. Given the long-horizon nature and extremely non-convex learning landscape of these tasks, we leverage diffusion models due to their strengths in non-greedy decision-making and long-horizon scalability. Preliminary studies in the context of autonomous navigation through icy waters—a practical instance of non-prehensile NAMO—have demonstrated promising performance compared to state-of-the-art planners.

<p style="margin-top: 40px;"></p>
---

## Bench-NPIN: Benchmarking Non-prehensile Interactive Navigation
<img style="float: right; padding-left:20px; padding-bottom: 150px;" src="/assets/benchnpin_intro.gif" width="300" height="470">

Mobile robots often operate in unstructured environments where obstacles and objects are movable. Navigation in such environments is known as interactive navigation, where task completion requires interactions with movable objects. Non-prehensile interactive navigation focuses on non-grasping interaction strategies such as pushing. While research in this area is growing, evaluation remains inconsistent due to case-specific setups. We present Bench-NPIN, the first comprehensive benchmark for non-prehensile interactive navigation. Bench-NPIN includes multiple components: 1) a comprehensive range of simulated environments for non-prehensile interactive navigation tasks, each with varying levels of complexity; 2) a set of evaluation metrics that capture unique aspects of interactive navigation, such as efficiency, interaction effort, and partial task completion; and 3) demonstrations using Bench-NPIN to evaluate example implementations of established baselines across environments. Bench-NPIN is also now an open-source Python library with a modular design.

Under Review for IROS 2025 <br>
[[Paper](https://arxiv.org/pdf/2409.11326v1)][[Project Page](https://sites.google.com/view/bench-npin/home)][[Github](https://github.com/IvanIZ/BenchNPIN)]
<br>
<p style="margin-top: 40px;"></p>
---

## Autonomous Navigation in Ice-Covered Waters with Learned Predictions on Ship-Ice Interactions
<img style="float: right; padding-left:20px;" src="/assets/method_video_fps7.gif" width="400" height="225">

Autonomous navigation in ice-covered waters poses significant challenges due to the frequent lack of viable collision-free trajectories. When complete obstacle avoidance is infeasible, it becomes imperative for the navigation strategy to minimize collisions. Additionally, the dynamic nature of ice, which moves in response to ship maneuvers, complicates the path planning process. To address these challenges, we propose a novel deep learning model to estimate the coarse dynamics of ice movements triggered by ship actions through occupancy estimation. To ensure real-time applicability, we propose a novel approach that caches intermediate prediction results and seamlessly integrates the predictive model into a graph search planner. We evaluate the proposed planner both in simulation and in a physical testbed against existing approaches and show that our planner significantly reduces collisions with ice when compared to the state-of-the-art.

ICRA 2025 <br>
[[Paper](https://arxiv.org/pdf/2409.11326v1)][[Project Page](https://sites.google.com/view/predictive-asv-nav/)][[Github](https://github.com/IvanIZ/predictive-asv-planner)]
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
