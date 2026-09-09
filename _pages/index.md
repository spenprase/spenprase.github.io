---
layout: splash
title: " "
permalink: /
hidden: true
header:
  overlay_color: "#222222" #"#5e616c"
  overlay_filter: "0.2"
  overlay_image: assets/images/banners/IMG_1354.JPG
  # actions:
  #   - label: "About Me"
  #     url: "/about/"
  caption: "Aklavik Range, NWT, Canada"

# Sidebar profile turned off — bio now lives in the intro block below
author_profile: false

#
feature_row:
  - image_path: /assets/images/IMG_0573.JPG
    image_size: 150px
    alt: "Arctic Alluvial Fans"
    title: "Arctic Alluvial Fans"
    url: "http://spenprase.github.io/research/"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: assets/images/Dartmouth/kettlebox_prep2.JPG
    alt: "Glacial Kettle Experiments"
    image_size: 150px
    title: "Glacial Kettle Experiments"
    url: "http://spenprase.github.io/research/"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: assets/images/Dartmouth/plow_presettle.JPG
    alt: "Post-glacial and Post-settlement change in the upper Mississippi River Valle"
    image_size: 150px
    title: "Post-glacial and Post-settlement change in the upper Mississippi River Valley"
    url: "http://spenprase.github.io/research/"
    btn_label: "Read More"
    btn_class: "btn--inverse"
---

<style>
html, body {
  overflow-x: hidden;
}
.home-section {
  position: relative;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  width: 100vw;
  flex-shrink: 0;
  box-sizing: border-box;
}
</style>

<div class="home-section" style="background-color: #f4f1ec; padding: 2.5rem 1.5rem;">
  <div style="display: flex; align-items: center; gap: 2.5rem; flex-wrap: wrap; max-width: 1000px; margin: 0 auto;">
    <div style="flex: 1 1 33%; min-width: 250px; max-width: 340px;">
      <img src="/assets/images/IMG_1834.JPG" alt="Shanti Penprase" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover; border-radius: 8px;">
    </div>
    <div style="flex: 1 1 55%; min-width: 250px;">
      <h1 style="margin-bottom: 0.25rem;">Dr. Shanti B. Penprase</h1>
      <p style="font-size: 1.1rem; font-weight: 600; color: #6f6f6f; margin-top: 0;">Guarini Dean's Postdoctoral Fellow, Department of Earth &amp; Planetary Sciences, Dartmouth College</p>
      <p>I study how climate, glaciation, and human land use shape landscapes over timescales ranging from millennia to the present day. My work spans Arctic fluvial and lacustrine systems, glacial meltwater routing, and the long-term impacts of agriculture on erosion.</p>
    </div>
  </div>
</div>

<div class="home-section" style="background-color: #607744; padding: 1rem 0.5rem; color: #ffffff;">
  <h2 style="text-align: center; color: #ffffff; margin-top: 0; margin-bottom: 0.75rem; font-size: 1.4rem;">Research Projects</h2>
  <div class="feature-row-skinny" style="max-width: 750px; margin: 0 auto; font-size: 0.75rem;">
  {% include feature_row %}
  </div>
</div>

<style>
.feature-row-skinny .archive__item-title {
  color: #ffffff;
  font-size: 1rem;
  margin-top: 0.4rem;
  margin-bottom: 0.2rem;
}
.feature-row-skinny .archive__item-excerpt,
.feature-row-skinny .archive__item-excerpt p {
  display: none;
}
.feature-row-skinny .btn--inverse {
  background-color: #ffffff;
  color: #607744;
  border-color: #ffffff;
  padding: 0.3em 0.8em;
  font-size: 0.75rem;
}
.feature-row-skinny .feature__wrapper {
  margin-bottom: 0;
}
</style>