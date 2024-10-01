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

I am a Research Scientist at [Epic Games](https://www.epicgames.com) working on developing next generation digital humans.
Previously, I did my PhD in Computer Graphics and Computer Vision at the [Max-Planck Institute for Informatics](https://www.mpi-inf.mpg.de/departments/computer-graphics) with [Prof. Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt/). I spent a year at [Weta Digital](https://www.wetafx.co.nz/) and lead a group on Optical Performance Capture at the [Max-Planck Center for Visual Computing and Communication](https://www.mpc-vcc.org/). I then cofounded [The Captury](https://www.thecaptury.com/) to bring a real-time markerless motion capture system to market, and moved to [Facebook Reality Labs](https://www.facebook.com/careers/life/facebook-reality-labs-turning-ideas-into-realities) to start working on full body virtual humans, before joining Epic in 2020.

My research interests span a wide range of topics from computer graphics, geometric modeling, animation, and computer vision. My main focus lies on developing new approaches and tools to enable creating and controlling fully photorealistic and believable digital human avatars.

### Projects
##### ML Deformer
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mldeformer.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        At EPIC I developed the ML model driving Unreal Engine's [ML Deformer](https://www.unrealengine.com/marketplace/en-US/product/ml-deformer-sample) plugin that can be used to create a high-fidelity next-generation character with deformations driven by full muscle, flesh, and cloth simulation running in real-time. 
    </div>
</div>


### Publications
###### (in reverse chronological order)

<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
