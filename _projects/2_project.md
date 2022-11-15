---
layout: page
title: BSc thesis
description: Control system design for EUROBOT Competition
img: assets/img/Bsc_robot1.jpg
importance: 2
category: work
selected: true
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_robot.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
The control system consists of:
- *Visual-aid* grabbing system
- Perception system based on *EKF* and *Particle filter*
- Planning & navigation system based on *Dijkstra* (global planner) and *TEB*(local planner)
- Main controller with work flow scheduling

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_controlsystem.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Visual aid manipulation of samples with QR code.
- QR code position & oriention detection
- Inverse kinematics calculation

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_manipulator.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_robot2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_visual.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


Map Perception:
- grid map based on Gmapping
- tried visual SLAM
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_background.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_Map.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_robotvslam.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Particle filter localization
- obstacle cost map 
- eliminate accumulative error

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_costmap.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_localization.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Planning based on via points
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Bsc_navigation.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
