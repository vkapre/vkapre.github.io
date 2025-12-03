---
layout: page
title: Material Card Development 
description: Experimental characterization and model calibration (microstructure, mechanical, thermal, viscoelastic) to generate validated material cards for 3D printing simulations.
img: assets/img/p3_thumb.png
importance: 3
category: work
related_publications: true
---

**Overview**  
Developed complete, orthotropic material cards for three carbon-fiber-reinforced thermoplastics (50% CF-PPS, 20% CF-PEI, 25% CF-PESU), enabling accurate extrusion-based AM simulations. Work conducted with Techmer and Lockheed Martin. {% cite barocio2022validated %}

<div class="row">
    <div class="col-sm-10 col-md-8 mx-auto mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/p3_2.png"
        title="Experimental-to-simulation workflow for material card generation"
        class="img-fluid rounded z-depth-1" style="max-width: 90%;" %}
    </div>
</div>
<div class="caption">
    Experimental-to-simulation workflow for material card generation.
</div>

**Approach**  
- Printed and tested coupons in printing, transverse, and stacking directions  
- Quantified fiber-orientation tensors using optical microscopy and X-ray CT  
- Performed DMA for viscoelastic behavior (Prony-series fitting)  
- Used DSC to characterize crystallization and melting profiles  
- Compiled complete orthotropic property sets for final material cards  

<div class="row">
    <div class="col-sm-10 col-md-8 mx-auto mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/p3_3.png"
        title="Material properties and corresponding ASTM standards"
        class="img-fluid rounded z-depth-1" style="max-width: 90%;" %}
    </div>
</div>
<div class="caption">
    Required properties and corresponding ASTM standards.
</div>

**Key Results**  
- Delivered fully validated material cards for all three material systems  
- Implemented cards in ADDITIVE-3D; validated part deformation accuracy  
- Produced comprehensive technical documentation for partners  

**Impact**  
Provides physics-based material inputs for AM simulations, improving deformation prediction and enabling reliable parametric studies for design and process optimization.

**Tools**  
DSC, DMA, TGA, X-ray CT, optical microscopy, MTS tensile frames, MATLAB, Python, ADDITIVE-3D
