---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About Me

I am a Senior Engineering Physics student at Cornell University interested in pursuing an accelerated M.Eng in Mechanical Engineering and gaining professional experience in hardware design for sensor-rich and autonomous systems. During the past three years, I have designed several underwater pressure vessels for Cornell's AUV team, iterated over several prototypes of eDNA samplers and underwater acoustic systems at Acbotics Research, and optimized a high-energy x-ray experimental apparatus in the Franck Lab at Cornell to measure Intra-Atomic Bremsstrahlung (IAB). I am drawn towards projects with unique constraints and challenging environments where I can leverage my applied physics background to inform my designs.

I am currently seeking Summer 2027 internships in robotics, aerospace, and hardware R&D as well as full-time employment starting in Spring 2028.

Outside of classes and engineering projects, I enjoy running, hiking, and being outdoors! When the weather is warm, I like planning small camping trips and day hikes. Once colder winter days arrive, I can be found teaching new tabletop games to my friends or reading from my chess book library.

## All Projects

### Acbotics

<div class="research-grid">

<a href="{{ site.url }}{{ site.baseurl }}/acbotics/#acsample-production" class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/acbotics/AcSample_CADFull.JPG" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">AcSample Production</h4>
<p class="research-desc">*January 2026, May 2026 - August 2026*</p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/acbotics/#acsample-prototype" class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/acbotics/Large_AcSample_Prototype_Full.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">AcSample Prototype</h4>
<p class="research-desc">*May 2025 - August 2025*</p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/acbotics/#plutos-source-box" class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/acbotics/PLUTOS_Source_Box_Assembly.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">PLUTOS Source Box</h4>
<p class="research-desc">*May 2025 - August 2025*</p>
</div>
</a>

</div>

### CU AUV

<div class="research-grid">

<a href="{{ site.url }}{{ site.baseurl }}/cuauv/#uhpv-orions-pressure-vessel" class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/cuauv/Orion_Full.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">UHPV (Orion's Pressure Vessel)</h4>
<p class="research-desc">*Designed Fall 2024, Fabricated/Assembled Spring 2025*</p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/cuauv/#summer-lead-robosub-2024-3rd-place-overall" class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/cuauv/Competition_TeamPic.PNG" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Summer Lead, RoboSub 2024</h4>
<p class="research-desc">*May 2024 - August 2024, Competition Week August 5-11*</p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/cuauv/#downcam-enclosure" class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/cuauv/Downcam_Full.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Downcam Enclosure</h4>
<p class="research-desc">*Designed Fall 2023, Fabricated/Assembled Spring 2024*</p>
</div>
</a>

</div>

### Academic

<div class="research-grid">

<a href="{{ site.url }}{{ site.baseurl }}/other/#gamma-ray-spectroscopy-lab" class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/other/GammaSpec.JPG" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Gamma Ray Spectroscopy</h4>
<p class="research-desc">*PHYS 4410 - Advanced Physics Lab*</p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/other/#torque-wrench" class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/other/Screenshot 2026-08-02 114417.png" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Torque Wrench</h4>
<p class="research-desc">*MAE 3720 - Mechanics of Engineering Materials.*</p>
</div>
</a>

<a href="{{ site.url }}{{ site.baseurl }}/other/#cavendish-balance" class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/other/Cavendish_Full.JPG" class="research-thumb" alt=" ">
<div class="research-body">
<h4 class="research-title">Cavendish Balance</h4>
<p class="research-desc">*PHYS 4410 - Advanced Physics Lab*</p>
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
