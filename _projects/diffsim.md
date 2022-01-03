---
layout: page
title: Differentiable simulation for physical system identifiaction
description: Quentin Le Lidec, Igor Kalevatykh, Ivan Laptev, Cordelia Schmid, Justin Carpentier, IEEE Robotic and Automation Letters
img: assets/img/sim_archi.png
importance: 2
category: work
--- 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/sim_archi.png title: "Differentiable simualtion" class: "img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Architecture of a differentiable simulator. Differentiability can be exploited to retrieve physical parameters from experiments.
</div>
In this paper, we introduce a new algorithm for physical simulation and propose a way to make it differentiable. The new differentiable simulator is applied to physical system identification.

The code of the differentiable solver is available at this [link](https://github.com/quentinll/diffqcqp)

For more details, the paper is available on [HAL](https://hal.archives-ouvertes.fr/hal-03025616/) and an introductory video containing a demo is available on Youtube:

<iframe width="560" height="315" src="https://www.youtube.com/embed/d248IWMLW9o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

The video of our ICRA presentation is also available:

<iframe width="560" height="315" src="https://www.youtube.com/embed/pIOuvVUmfsE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

You can cite this work with:

{% raw %}
```
@ARTICLE{9363565,

  author={Le Lidec, Quentin and Kalevatykh, Igor and Laptev, Ivan and Schmid, Cordelia and Carpentier, Justin},

  journal={IEEE Robotics and Automation Letters}, 

  title={Differentiable Simulation for Physical System Identification}, 

  year={2021},

  volume={6},

  number={2},

  pages={3413-3420},

  doi={10.1109/LRA.2021.3062323}}

```
{% endraw %}
