---
layout: page
title: project 1
description: 3D modelling of the radiation transfer in PDS 70
img: assets/img/12.jpg
importance: 1
category: PhD
---

PDS 70 is as T-Tauri star surrounded by a protoplanetary disk whose existence
was determined via analysis of the infrared excess. With the advent of ALMA, the
high resolution and sensitivity allowed to image the spacially resolved disk
unvealing the presence of inner and outer disk, and a central cavity ~20 au wide.

Aditionally, observations with the VLT/SPHERE instrument demonstrated the presence
an embedded planet in the cavity whose existnece was further confirmed with
observations of gas accretion which also detected a second source of accrection
at 30 au. That second source was later confirmed to have planetary nature and
once again ALMA confirmed that it is surrounded by a circumplanetary disk.

Therefore, PDS 70 is the first system that allowed us to confirm the long-standing
theory that planets form in disks of gas and dust.

In my first project, I developed a 3D model for the transfer of the continuum
radiation in the disk. I worked with ALMA and VLT/SPHERE archival data and my
goal was to determine a set of parameters able to 
reproduce the observations by VLT/SPHERE in polarised light (due to scatter with
  the dust grains in the atmosphere of the disk) and with ALMA. The model also
includes the planet PDS 70 c as a second source of heating which is surrounded
by the CPD.

Our model suggest an optically thin inner disk, a dust depleted cavity with a
maximum dust column density of 1e-5 gcm-2, and dust filtration at the outer edge of
the cavity. For the CPD, the model suggests it is an optically thick structure
and we constrained the dust budget to the range 0.07-0.7 Earth masses.

This research was published in Astronomy and Astrophysics main journal.   

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
