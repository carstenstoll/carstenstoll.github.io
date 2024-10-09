---
layout: about
title: home
permalink: /
subtitle: Research Scientist at <a href='https://www.epicgames.com'>Epic Games</a>.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I am a Research Scientist at [Epic Games](https://www.epicgames.com), specializing in the development next generation digital humans.

I earned my PhD in Computer Graphics and Computer Vision from the [Max-Planck Institute for Informatics](https://www.mpi-inf.mpg.de/departments/computer-graphics) with [Prof. Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt/). I also lead a group on Optical Performance Capture at the [Max-Planck Center for Visual Computing and Communication](https://www.mpc-vcc.org/) and spent a year as visiting researacher at [Weta Digital](https://www.wetafx.co.nz/). I cofounded [The Captury](https://www.thecaptury.com/), a company focused on real-time markerless motion capture, and then joined [Facebook Reality Labs](https://www.facebook.com/careers/life/facebook-reality-labs-turning-ideas-into-realities) to work on full body virtual humans, before joining Epic in 2020.

My research interests span a wide range of topics from computer graphics, geometric modeling, animation, and computer vision. My primary goal is to advance the technology and tools to create and control fully photorealistic and believable digital human avatars.

### Projects
##### ML Deformer
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mldeformer.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        At <a href="https://www.epicgames.com">Epic Games</a> I developed the ML model driving Unreal Engine's <a href="https://www.unrealengine.com/marketplace/en-US/product/ml-deformer-sample">ML Deformer</A> plugin that can be used to create a high-fidelity next-generation character with deformations driven by full muscle, flesh, and cloth simulation running in real-time. 
    </div>
</div>
##### Momentum
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/momentum.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        At Facebook/Oculus Research I developed the <a href="https://facebookincubator.github.io/momentum/">Momentum</A> library for human kinematics and numerical optimization that was used to prototype markerless motion capture algorithms and was used for early versions of the Oculus VR headset upper body tracking.
    </div>
</div>

### Publications
###### (in reverse chronological order)

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
