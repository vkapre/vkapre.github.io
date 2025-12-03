---
layout: page
title: Single-Screw Extrusion of Polymer Composites
description: Modeling pellet motion, melting, deformation, and fiber length attrition to capture the solid–melt transition and its effect on extrudate quality. Ph.D. thesis work.
img: assets/img/p1_1.gif
importance: 1
category: work
related_publications: true
---

**Overview**  
Developed a unified DEM–FEM–analytical modeling framework during my Ph.D. to predict pellet motion, melting, deformation, and fiber breakage for long-discontinuous fiber-reinforced polymer pellets. This work appears in my thesis and related publications {% cite kapre2024fiber%}, {%cite kapre2025single%}, {%cite kapre2024modeling%}.

<div class="row">
    <div class="col-sm-10 col-md-8 mx-auto mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/p1_2.png"
        title="DEM pellet trajectories, melt progression, and fiber-length distribution" 
        class="img-fluid rounded z-depth-1" style="max-width: 90%;" %}
    </div>
</div>
<div class="caption">
    DEM pellet trajectories, melt progression, and fiber-length distribution along the screw.
</div>

**Approach**  
- DEM (LIGGGHTS) for pellet motion and kinematics  
- FEM (ABAQUS) for heat transfer and melting of individual pellets  
- Beam theory + Weibull model for pellet deformation and fiber breakage  
- Coupled these into a melt progression + fiber-length evolution framework  

<div class="row">
    <div class="col-sm-10 col-md-8 mx-auto mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/p1_3.png"
        title="Predicted fiber-length distributions and melt-state evolution" 
        class="img-fluid rounded z-depth-1" style="max-width: 90%;" %}
    </div>
</div>
<div class="caption">
    Predicted fiber-length distributions and melt-state evolution along the screw.
</div>

**Key Results**  
- Pellets recirculate primarily in the second half of the screw, aligning with rapid outside–in melting  
- Fiber breakage initiates once the outer pellet layer melts  
- Starve-feeding reduces residence time and fiber attrition; high RPM can cause incomplete melting  
- Predicted bimodal fiber-length distributions match experiments  

**Impact**  
Provides a quantitative basis to tune screw geometry, feeding mode, and processing conditions to preserve fiber length and improve composite performance; extensible to other thermoplastic and extrusion-based AM feedstocks.

**Tools**  
LIGGGHTS, ABAQUS, MATLAB, Python, HPC environment; Material: 40% CF-PPS
