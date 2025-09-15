---
layout: page
title: Biplane Shape Sensing
description: Modeling and Sensing
img: assets/img/projection_planes.jpg
importance: 6
category: work
related_publications: true
---

Building off our initial work in {% cite lawson2023model %}, we wanted to leverage biplane fluoroscopy to not only capture the pose of the bending plane, but also the bending shape and axial "roll" of the catheter. We leveraged the radiopacity of marker bands typically placed in the catheter tip, and placed these markers in a patterned shape along the distal segment of the catheter.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/radiopaque_marker_tip_v2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The radiopaque marker band of an off-the-shelf catheter. From {% cite lawson2023model %}.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/marker_band_prototype.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The radiopaque marker bands placed patterned around a radiolucent catheter. From {% cite lawson2023model %}.
</div>

This combination of markers are segmented in each plane and reconstructed in 3D to serve as the basis for solving the shape and orientation of the catheter segment.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/marker_band_estimation_workflow_v2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Workflow of shape estimation for the slim catheter prototype. From {% cite lawson2023model %}.
</div>

We then deployed this approach under fluoroscopy for many static shape configurations, and even during a catheter insertion in a phantom model.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/RAL_experimental_setup.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Estimated shape overlaid on fluoroscopic images. From {% cite lawson2023model %}.
</div>