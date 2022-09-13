---
title:
layout: post
permalink: /projects/
published: true
---

# Detection of Real and Fake Images

Trained models with the pre-trained dataset (ProGAN and SNGAN) and produced fake images using them. Classified images as real or GAN-generated using the GAN fingerprints. Implemented the project using Python (OpenCV)



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
