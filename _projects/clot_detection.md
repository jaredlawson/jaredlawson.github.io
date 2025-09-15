---
layout: page
title: Clot Detection
description: Sensing and ML
img: assets/img/catheter_in_clot.jpg
importance: 4
category: work
related_publications: true
---

To treat stroke, catheters are sent up the cerebral arteries to localize and retrieve blood clots. However, under fluoroscopy visualization alone, it is impossible to directly visualize the clot and results in some procedures needing to be repeated to ensure recanalization of the vessel. We developed a method we refer to as vacuum excitation, which enables detection of the clot at the catheter's tip by monitoring the pressure profile within the catheter. In an in-vitro study with expert neurointerventionalists, we showed our that experts were three times more likely to accurately localize the clot with our system compared to fluoroscopic presentation {% cite lawson2024endovascular %}

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/TBME-01608-2023-Website-Image.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This shows a mockup of our system, where the oscillating syringe (top right) creates the pressure signal which classifies clot contact (bottom right). Image from https://www.embs.org/tbme/articles/endovascular-detection-of-catheter-thrombus-contact-by-vacuum-excitation/.
</div>
