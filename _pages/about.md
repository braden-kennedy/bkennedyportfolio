---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## All Projects

### Acbotics

<div class="research-grid" markdown="0">

<a href="{{ site.url }}{{ site.baseurl }}/acbotics/#acsample-production">
<div class="research-card">
  <img src="{{ site.url }}{{ site.baseurl }}/images/acbotics/AcSample_CADFull.JPG" class="research-thumb" alt="">
  <div class="research-body">
    <h4 class="research-title">AcSample Production</h4>
    <p class="research-desc"><em>January 2026, May 2026 - August 2026</em></p>
  </div>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/acbotics/#acsample-prototype" class="research-card" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/acbotics/Large_AcSample_Prototype_Full.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">AcSample Prototype</h4>
<p class="research-desc"><em>May 2025 - August 2025</em></p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/acbotics/#plutos-source-box" class="research-card" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/acbotics/PLUTOS_Source_Box_Assembly.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">PLUTOS Source Box</h4>
<p class="research-desc"><em>May 2025 - August 2025</em></p>
</div>
</a>

</div>

### CU AUV

<div class="research-grid" markdown="0">

<a href="{{ site.url }}{{ site.baseurl }}/cuauv/#uhpv-orions-pressure-vessel" class="research-card" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/cuauv/Orion_Full.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">UHPV (Orion's Pressure Vessel)</h4>
<p class="research-desc"><em>Designed Fall 2024, Fabricated/Assembled Spring 2025</em></p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/cuauv/#summer-lead-robosub-2024-3rd-place-overall" class="research-card" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/cuauv/Competition_TeamPic.PNG" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Summer Lead, RoboSub 2024</h4>
<p class="research-desc"><em>May 2024 - August 2024, Competition Week August 5-11</em></p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/cuauv/#downcam-enclosure" class="research-card" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/cuauv/Downcam_Full.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Downcam Enclosure</h4>
<p class="research-desc"><em>Designed Fall 2023, Fabricated/Assembled Spring 2024</em></p>
</div>
</a>

</div>

### Academic

<div class="research-grid" markdown="0">

<a href="{{ site.url }}{{ site.baseurl }}/other/#gamma-ray-spectroscopy-lab" class="research-card" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/other/GammaSpec.JPG" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Gamma Ray Spectroscopy</h4>
<p class="research-desc"><em>PHYS 4410 - Advanced Physics Lab</em></p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/other/#torque-wrench" class="research-card" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/other/Screenshot 2026-08-02 114417.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Torque Wrench</h4>
<p class="research-desc"><em>MAE 3720 - Mechanics of Engineering Materials.</em></p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/other/#cavendish-balance" class="research-card" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/other/Cavendish_Full.JPG" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Cavendish Balance</h4>
<p class="research-desc"><em>PHYS 4410 - Advanced Physics Lab</em></p>
</div>
</a>

</div>


<div class="section-card">
<div class="pi-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/{{ site.photo }}" class="pi-photo" alt="{{ site.name }}" loading="lazy">
<div>
<h3 class="pi-name">{{ site.name }}</h3>
<p style="font-style: italic; color: var(--text-secondary);">{{ site.title }}, {{ site.institution }}</p>
<div class="pi-links">
{% if site.email %}<a href="mailto:{{ site.email }}" class="icon-link" title="Email"><i class="fa-solid fa-envelope"></i></a>{% endif %}
{% if site.links.cv and site.links.cv != "" %}<a href="{{ site.url }}{{ site.baseurl }}/{{ site.links.cv }}" class="icon-link" title="CV"><i class="ai ai-cv"></i></a>{% endif %}
{% if site.links.github and site.links.github != "" %}<a href="{{ site.links.github }}" class="icon-link" title="GitHub"><i class="fa-brands fa-github"></i></a>{% endif %}
</div>
</div>
</div>
</div>

{% if site.data.awards %}
<div class="section-card">
<h3>Recent Awards & Fellowships</h3>
<ul>
{% for award in site.data.awards %}
<li>{{ award.name | replace: "-","&#8211;" }}</li>
{% endfor %}
</ul>
</div>
{% endif %}
