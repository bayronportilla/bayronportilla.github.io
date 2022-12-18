---
layout: page
title: Modelling the continuum emission from the PDS 70 disk
description:
img:
importance: 1
category: PhD
---

PDS 70 is a T-Tauri star with a protoplanetary disk first discovered via infrared
excess analysis. The high resolution and sensitivity of ALMA allowed to spatially resolve the disk in the continuum revealing the presence of an inner and an outer disk, and a central cavity ∼ 20 au wide. Additionally, several observations in the near infrared demonstrated the presence of a planet (PDS 70 b) embedded in the cavity that was confirmed later on with $$\mathrm{H}\alpha$$ observations.
The later observation also detected a second source of accretion close to the outer
dust ring that was later confirmed to have planetary nature (PDS 70 c). A subsequent ALMA
campaign confirmed that the c planet is surrounded by a circumplanetary disk (CPD).

Therefore, PDS 70 is the first observational confirmation for the long-standing hypothesis that planets form embedded in disks of gas and dust around young stellar objects.

For my first PhD paper, I used the continuum radiative transfer code MCMax3D to develop a 2D continuum radiative transfer model for the PDS 70 disk. I analysed ALMA and VLT/SPHERE archival data of the spatially resolved disks to find
a set of parameters suitable to explain the observations. Our model suggest an optically thin inner disk, a dust
depleted cavity with an upper limit for the dust column density of $$ 10^{-5} \ \mathrm{g}\ \mathrm{cm}^{-2}$$. Dust filtration at the edge of the cavity can explain the measurement set but due to the multiple degeneracies among the parameters, a homogeneous size distribution across the disk could do it as well.  

Then, I extended the model to three dimensions to include a second
source of photons to simulate the planet PDS 70 c and its CPD. The model suggests the CPD is an optically thick structure
and constrained the amount of dust to be in the range $$0.07-0.7 \ M_\oplus$$.

If you are interested in learning more, please take a look to the [publication](https://www.aanda.org/articles/aa/full_html/2022/02/aa41764-21/aa41764-21.html).   

<div class="row justify-content-sm-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/eso2111b.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/CPD_submm.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>

</div>
<div class="caption">
    Left: Sub-mm image towards PDS 70 taken with ALMA (Benisty et al. 2021).
    Right: Model ray-traced at 855 micron for three different CPD's dust masses.   
</div>
