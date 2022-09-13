---
title:
layout: post
permalink: /projects/
published: true
---


---
### Detection of Real and Fake Images

Trained models with the pre-trained dataset (ProGAN and SNGAN) and produced fake images using them. Classified images as real or GAN-generated using the GAN fingerprints. Implemented the project using Python (OpenCV).

---
### AR Watch App

Created an interactive AR app, where Unity engine was used to obtain a virtual 3D preview of the watch, Vuforia was used to identify and set the pre-defined target like the wrist, and a mobile app facilitated swapping of watch straps and colors to enable shoppers to try out the watch.

---
### OpenMP, MPI, CUDA implementation of DFT

Found the normalized frequency of a random signal using DFT, parallelized the code using OpenMP, MPI and CUDA, and computed the execution time and speed-up to obtain the optimum number of processors to perform the task.

---
### Micro-architecture Design

Coded the various components of the processor, such as floating-point adder, floating-point multiplier, logic unit, barrel shifter, register file, instruction fetch unit, and cache, from scratch using Verilog.

---
### Redesigned the Yale School of Art website

Used various design laws, such as Fitts’ Law, Hick and Hyman Law, Gestalt’s Law, Asimov’s Laws, and Pareto’s Law, along with various design principles, such as Skeuomorphism, Dual Coding Theory, and Navigational Design to redesign the website and make it more user-friendly. Designed the website using AdobeXD.

---
<!-- <div class="ProjectContainer">

	<div class="gallery">


  {% for project in site.projects %}

  {% if project.redirect %}
  <div class="projectTile">
          <a href="{{ project.redirect }}" target="_blank">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>

  {% else %}

  <div class="projectTile">
          <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
          <span>
              <h2>{{ project.title }}</h2>
              <br/>
              <p>{{ project.description }}</p>
          </span>
          </a>
  </div>

  {% endif %}

  {% endfor %}

	</div>

</div> -->
