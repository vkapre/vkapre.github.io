---
layout: page
title: Skills
permalink: /skills/
description:
nav: true
nav_order: 3
---

<style>
  .skills-section{display:flex;gap:2rem;align-items:flex-start;margin:2.0rem 0;border-radius:12px;overflow:hidden;box-shadow:0 2px 10px rgba(0,0,0,0.05);}
  .skills-left{flex:0 0 250px;max-width:250px;color:#e7edf2;font-weight:700;font-size:1.05rem;letter-spacing:.01em;display:flex;align-items:center;justify-content:flex-start;padding:1.2rem 1rem 1.2rem 1.4rem;}
  .skills-right{flex:1;padding:1.0rem 1.0rem;background:#101418;border-top-right-radius:12px;border-bottom-right-radius:12px;}
  /* Section summary line */
  .section-summary{margin:.25rem .4rem 0 .4rem;color:#a7b0b7;font-size:.95rem;line-height:1.45;}
  .summary-sep{height:8px}
  /* Item rows with per-line right column */
  .line{display:flex;gap:1rem;align-items:flex-start;padding:.35rem .4rem;border-bottom:1px dashed rgba(255,255,255,0.06);}
  .line:last-child{border-bottom:none;}
  .bullet{margin-right:.25rem;opacity:.6;min-width:1rem}
  .left{flex:1;min-width:220px;}
  .right{min-width:260px;text-align:right;opacity:.95;white-space:normal;}
  /* Dark muted themes */
  .theme-1 .skills-left{background:#244452;}
  .theme-1 .skills-right{background:#0e1419;}
  .theme-2 .skills-left{background:#3a334d;}
  .theme-2 .skills-right{background:#12141a;}
  .theme-3 .skills-left{background:#2f4a3b;}
  .theme-3 .skills-right{background:#111714;}
  .theme-4 .skills-left{background:#3d454a;}
  .theme-4 .skills-right{background:#121517;}
  /* Mobile */
  @media (max-width: 820px){
    .line{flex-direction:column;gap:.2rem;}
    .right{text-align:left;}
  }
</style>

<!-- 1) Modeling & Simulation -->
<div class="skills-section theme-1">
  <div class="skills-left">Modeling & Simulation</div>
  <div class="skills-right">

    <div class="section-summary">
      Pellet extrusion and Additive manufacturing workflows using finite element, discrete element methods: meshing, solver setup and tuning, and results post‑processing.
    </div>
    <div class="summary-sep"></div>

    <div class="line">
      <div class="bullet">•</div>
      <div class="left">ABAQUS (FEA)</div>
      <div class="right">Advanced ★★★★☆</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">LIGGGHTS (DEM)</div>
      <div class="right">Intermediate ★★★☆☆</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">ANSYS (FEA)</div>
      <div class="right">Beginner ★★☆☆☆</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Additive-3D</div>
      <div class="right">Advanced ★★★★☆</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">MATLAB</div>
      <div class="right">Advanced ★★★★☆</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Python</div>
      <div class="right">Intermediate ★★★☆☆</div>
    </div>
  </div>
</div>

<!-- 2) Characterization -->
<div class="skills-section theme-2">
  <div class="skills-left">Characterization</div>
  <div class="skills-right">

    <div class="section-summary">
      Microstructural, mechanical, thermal and viscoelastic characterization of orthotropic materials (fiber-reinforced polymer composites).
    </div>
    <div class="summary-sep"></div>

    <div class="line">
      <div class="bullet">•</div>
      <div class="left">X-ray CT</div>
      <div class="right">3D imaging, porosity analysis</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Optical Microscopy</div>
      <div class="right">Fiber orientation, length measurements</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Faro ARM Laser Scanner</div>
      <div class="right">Surface deformation analysis</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">DSC, TGA, DMA</div>
      <div class="right">Thermal/viscoelastic characterization</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Tensile / Compression / Shear</div>
      <div class="right">Mechanical testing</div>
    </div>
  </div>
</div>

<!-- 3) Other Tools and Software -->
<div class="skills-section theme-3">
  <div class="skills-left">Other Tools and Software</div>
  <div class="skills-right">

    <div class="section-summary">
      CAD, reverse engineering, and analysis pipelines supporting modeling and experiments.
    </div>
    <div class="summary-sep"></div>

    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Wolfram Mathematica</div>
      <div class="right">Symbolic and numerical computation</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">DIGIMAT</div>
      <div class="right">Micromechanical analysis</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Paraview</div>
      <div class="right">Visualization of DEM particles</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">SolidWorks</div>
      <div class="right">CAD modeling & assembly</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">ImageJ</div>
      <div class="right">Image processing</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">VG Studio</div>
      <div class="right">CT reconstruction and segmentation</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">VIC-3D</div>
      <div class="right">DIC strain measurements</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Waterjet</div>
      <div class="right">Sample prep, cutting</div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">TA Universal Analysis</div>
      <div class="right">Thermal analysis data processing</div>
    </div>
  </div>
</div>

<!-- 4) Collaboration & Communication -->
<div class="skills-section theme-4">
  <div class="skills-left">Collaboration & Communication</div>
  <div class="skills-right">

    <div class="section-summary">
      Reports, presentations, and cross‑functional coordination across academia and industry partners.
    </div>
    <div class="summary-sep"></div>

    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Technical writing and presentation</div>
      <div class="right"></div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Cross-disciplinary teamwork</div>
      <div class="right"></div>
    </div>
    <div class="line">
      <div class="bullet">•</div>
      <div class="left">Mentoring junior researchers</div>
      <div class="right"></div>
    </div>
  </div>
</div>
