---
layout: page
title: Xplainable RL
description: Self Driving Vehicles
img:
importance: 4
category: engineering
---

**XRL**: Explainable Reinforcement Learning for Autonomous Driving

Problem: Going from Planning to Control [(Text based) Challenge] in a vision language model.
* VLAM = VLM + A (action using DL/RL framework)
* Running optimized VLMs on edge deivces.

**Requirement**: How to obtain an interpretable navigation policy for intelligent driving agents trained using world
model with explainable RL for autonomous driving in real world setting (at action level).

* Training agents on World Models (Internal WM) using RL/IL.
* Existing explainable AI (XAI): Vision Language Action Models (VLAMs) techniques
* does not explain the underlying “action” driving policy for agents behavior.
* Require explainable RL for interpretable features, policy and learning process

Why?

* Current: Perception architectures based on explainable machine learning.
* Transition: LLMs (Large Language Models) → LWMs (Large World Models)
* Future: Cognitive Architectures based on explainable reinforcement learning.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Why XRL?
</div>

Explainable reinforcement learning is an emerging subfield of explainable ML.
The goal of XRL is to elucidate the decision-making process of reinforcement learning (RL)
agents in sequential decision-making settings. <a href="https://dl.acm.org/doi/10.1145/3616864">Explainable RL Review</a> Milani, Fie Fang CMU,2024) To understand: What the agents will do and why. A novel taxonomy for organizing the XRL.
Three high-level categories:
* ● Feature Importance,
* ● Learning process and Markov decision process, (LPM) and
* ● Policy-level (PL)

Why? RL is combined with the generalization and representational power of deep neural
networks, which is often required to achieve the desired performance on these tasks.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
