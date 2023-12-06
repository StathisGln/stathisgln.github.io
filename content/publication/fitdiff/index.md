---
title: 'FitDiff: Robust monocular 3D facial shape and reflectance estimation using Diffusion Models'
url: /fitdiff
layout: fitdiff
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Alexandros Lattas
  - Stylianos Moschoglou
  - Stefanos Zafeiriou 

date: '2023-02-06T00:00:00Z'
tags: []
# Display this page in the Featured widget?
featured: true
links:
#- name: ArXiv
#  url: 'https://arxiv.org/abs/2209.07366'
---

<section class="hero teaser">
  <div class="container is-max-desktop">
    <div class="hero-body">
      <video id="teaser" autoplay muted loop playsinline height="100%">
        <source src="./videos/fig1_1.mp4"
                type="video/mp4">
      </video>
      <h5 class="subtitle has-text-centered">
        FitDiff, a versatile multi-modal diffusion model, produces relightable facial avatars that seamlessly integrate into various commercial rendering platforms.
      </h5>
      <video id="teaser" autoplay muted loop playsinline height="100%">
        <source src="./videos/fig1_2.mp4"
                type="video/mp4">
      </video>
      <h5 class="subtitle has-text-centered">
        Given "in-the-wild" facial images, FitDiff reconstructs facial avatars consisting of facial shape and reflectance.
      </h5>
    </div>
  </div>
</section>
<br><br>
<section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 >Abstract</h2>
        <div class="content has-text-justified">
          <p>
            In this work, we present FitDiff, a diffusion-based 3D facial avatar generative model.
            This model accurately generates relightable facial avatars, utilizing an identity embedding
            extracted from an "in-the-wild" 2D facial image.
          </p>
          <p>
          Our multi-modal diffusion model concurrently outputs facial reflectance maps(albedo, specular, and normals)
          and shapes, showcasing great generalization capabilities.
          It is solely trained on an annotated subset of a public facial dataset, paired with 3D reconstructions.
          We revisit the typical 3D facial fitting approach by guiding a reverse diffusion process using perceptual and face recognition losses.
          </p>
          <p>
          Being the first LDM conditioned on face recognition embeddings, FitDiff reconstructs relightable human avatars,
            that can be used as-is in typical rendering engines, starting only from a single unconstrained facial image
            while achieving state-of-the-art performance.
          </p>
          <br>
        </div>
      </div>
    </div>
    <div class="columns is-centered">
      <div class="column is-full-width">
        <h2 class="title is-3">Method</h2>
      </h2>
      <video id="teaser" autoplay muted loop playsinline height="100%">
        <source src="./videos/method.mp4"
                type="video/mp4">
      </video>
        Starting from Gaussian noise, FitDiff concurently generates
        facial shape and reflectance maps (diffuse albedo, specular albedo and normals),
        conditioned on an identity embedding vector.
        During sampling, a novel guidance algorithm is applied for further control of the resulting facial avatar.
        Z<sub>T</sub>,Z<sub>k</sub> and Z<sub>k−1</sub> are visualized in the actual picture space for illustration purposes
      </p>
      </div>
    </div>
    <div class="columns is-centered">
      <div class="column is-full-width">
        <h2 class="title is-3">Unconditional Sampling</h2>
      </h2>
      </div>
    </div>
    <p>
      <video id="teaser" autoplay muted loop playsinline height="100%">
        <source src="./videos/fig3.mp4"
                type="video/mp4">
      </video>
    </p>
      <br>
      <p>
        FitDiff can  generate diverse facial identities without the need for pre-existing input.
        These assets offer significant potential across diverse applications, including enhancing
        existing datasets through augmentation and enrichment,
        as well as the creation of genuinely random identities for computer-based applications.
      </p>
  </div>
</section>


