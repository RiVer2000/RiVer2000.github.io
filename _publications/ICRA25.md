---
title: "Reactive Collision Avoidance for Safe Agile Navigation"
collection: publications
category: conferences
permalink: /publication/ICRA25
excerpt: 'The goal is to enable an agile aerial vehicle with an RGBD sensor to navigate safely from start to goal in unknown, dynamic environments. Our method combines nonlinear model predictive control with adaptive control barrier functions, directly linking perception-driven constraints to real-time planning and control'
date: 2025-05-20
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
paperurl: 'https://arxiv.org/pdf/2409.11962'
citation: 'A. Saviolo, N. Picello, J. Mao, R. Verma and G. Loianno, "Reactive Collision Avoidance for Safe Agile Navigation," <i>2025 IEEE International Conference on Robotics and Automation (ICRA), Atlanta, GA, USA, 2025, pp. 16125-16132, doi: 10.1109/ICRA55743.2025.11127284.</i>'
---

Reactive collision avoidance is essential for agile robots navigating complex and dynamic environments, enabling real-time obstacle response. However, this task is inherently challenging because it requires a tight integration of perception, planning, and control, which traditional methods often handle separately, resulting in compounded errors and delays. This paper introduces a novel approach that unifies these tasks into a single reactive framework using solely onboard sensing and computing. Our method combines nonlinear model predictive control with adaptive control barrier functions, directly linking perception-driven constraints to real-time planning and control. Constraints are determined by using a neural network to refine noisy RGB-D data, enhancing depth accuracy, and selecting points with the minimum time-to-collision to prioritize the most immediate threats. To maintain a balance between safety and agility, a heuristic dynamically adjusts the optimization process, preventing overconstraints in real time. Extensive experiments with an agile quadrotor demonstrate effective collision avoidance across diverse indoor and outdoor environments, without requiring environment-specific tuning or explicit mapping.