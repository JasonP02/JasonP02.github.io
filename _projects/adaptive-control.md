---
layout: project
title: "Adaptive PID Control Simulation"
subtitle: "Robotic arm trajectory control under external forces"
date: "October 2024 - December 2024"
status: "completed"
domain: robotics
image: "/assets/images/adaptive_control.jpg"
has_github: true
github: "https://github.com/jasonp02/adaptive-control"
has_report: true
report: "/assets/pdfs/adaptive_control_report.pdf"
---

## Overview
Implementation of adaptive control strategies for the Emika Panda robotic arm, focusing on maintaining circular trajectory under various external forces including wind disturbance and unconstrained mass handling.

## Technical Details
• Circular trajectory implementation
• Wind force disturbance simulation
• Adaptive controller development
• Comparison with Ziegler-Nichols method
• Performance analysis under varying conditions

I did this project with my friend, and I was responsible for the adaptive control and simulation.

<div class="tech-stack">
  <span class="tech-tag">Python</span>
  <span class="tech-tag">Control Systems</span>
  <span class="tech-tag">Robotics</span>
  <span class="tech-tag">Simulation</span>
</div>

## Key Learnings
• Advanced control system design
• Disturbance rejection techniques
• Simulation environment setup
• Performance analysis methods

## Challenges & Solutions
The primary challenge was implementing the wind disturbance simulation effectively. While we successfully demonstrated the adaptive controller's effectiveness under wind forces, we weren't able to fully implement the unconstrained mass scenario due to limitations with Mujoco implementation experience.

## Future Work
• Test multiple loading cases
• Implement unconstrained mass simulation
• Study effects of arm geometry on control
• Compare different control methodologies 