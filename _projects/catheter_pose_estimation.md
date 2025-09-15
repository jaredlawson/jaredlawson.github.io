---
layout: page
title: Pose Estimation
description: Modeling and Sensing
img: assets/img/projection_planes.jpg
importance: 5
category: work
related_publications: true
---

Catheters navigated in the brain are inserted, rotated about their central axis, and in the case of steerability, they can be deflected to bend in certain directions. As we look to automate or control these motions, we rely on pose estimation of where the catheters are and how they will move if steered from their current configuration. In the case of neurointervention, the only feedback modality available is biplane fluoroscopy, in which radiopaque features on the catheter are segmented in two views. In this work, we focus on recovering the full pose of a catheter's distal tip which includes both the position and orientation (including z-rotation). More results to come on this project!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/icra_experimental_setup.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This figure shows our mock biplane imaging setup, with the steerable catheter segmented in a side and front viewing plane. This image is from {% cite lawson2023model %}.
</div>
