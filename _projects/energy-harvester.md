---
layout: project
title: "Nonlinear Energy Harvester Analysis"
subtitle: "Magnetic suspension system dynamics study"
project_date: "November 2024 - December 2024"
status: "completed"
domain: other
image: "/assets/images/energy-harvester.png"
has_github: false
has_report: true
report: "/assets/pdfs/energy_harvester_report.pdf"
---

## Overview
Analysis and implementation of a nonlinear energy harvesting system based on magnetic suspension, following research by Alevras et al. The project involved studying chaotic behaviors and bifurcations in a magnetic energy harvester system.

## Technical Details
• Nonlinear system modeling.
• Chaotic behavior analysis.
• Bifurcation studies.
• Numerical analysis implementation.
• Secondary Sprott system J investigation.

The bifurcation study was the most challenging part of the project. I had to implement a numerical method to find the fixed points of the system and then use a bifurcation analysis to find the bifurcations. Here is one example of a bifurcation diagram I generated:

<div class="image-gallery">
  <img src="{{ '/assets/images/energy-harvester-bifurcation.png' | relative_url }}" alt="Bifurcation Diagram">
</div>

<div class="tech-stack">
  <span class="tech-tag">MATLAB</span>
  <span class="tech-tag">Nonlinear Dynamics</span>
  <span class="tech-tag">Mathematical Modeling</span>
</div>

## Key Learnings
• Nonlinear system analysis.
• Chaos theory applications.
• Numerical methods.
• Research paper implementation.

## Challenges & Solutions
The main challenge was accurately reproducing the complex dynamics described in the original research paper. This was addressed through careful implementation of numerical methods and validation against published results.