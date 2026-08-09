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

## Research

<div class="research-grid">

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/qed.svg" class="research-thumb" alt="Feynman diagram">
<div class="research-body">
<h4 class="research-title">Quantum Electrodynamics</h4>
<p class="research-desc">Development of the path integral formulation of quantum mechanics and its application to quantum electrodynamics (QED). This work introduced Feynman diagrams as a powerful tool for calculating particle interactions, providing an intuitive visual representation of complex quantum processes.</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/superfluidity.svg" class="research-thumb" alt="Superfluid helium">
<div class="research-body">
<h4 class="research-title">Superfluidity</h4>
<p class="research-desc">Quantum mechanical explanation of the behavior of liquid helium near absolute zero. Using path integral methods, we developed a microscopic theory of the lambda transition and explained the energy spectrum of excitations in superfluid helium, including the roton minimum.</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/partons.svg" class="research-thumb" alt="Parton model">
<div class="research-body">
<h4 class="research-title">Parton Model</h4>
<p class="research-desc">A model describing the internal structure of hadrons in terms of point-like constituents called partons. This framework proved essential for interpreting deep inelastic scattering experiments at SLAC and laid the groundwork for quantum chromodynamics (QCD).</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/quantum-computing.svg" class="research-thumb" alt="Quantum circuit">
<div class="research-body">
<h4 class="research-title">Quantum Computing</h4>
<p class="research-desc">Pioneering proposals for using quantum mechanical systems to perform computation. We demonstrated that classical computers cannot efficiently simulate quantum physics, motivating the development of quantum computers that exploit superposition and entanglement.</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/nanotechnology.svg" class="research-thumb" alt="Atomic manipulation">
<div class="research-body">
<h4 class="research-title">Nanotechnology</h4>
<p class="research-desc">Exploration of the physical possibilities of manipulating matter at the atomic scale. The talk "There's Plenty of Room at the Bottom" envisioned machines that could arrange atoms one by one, anticipating modern nanotechnology and molecular manufacturing.</p>
</div>
</div>

<div class="research-card">
<img src="{{ site.url }}{{ site.baseurl }}/images/research/weak-interactions.svg" class="research-thumb" alt="Weak interaction diagram">
<div class="research-body">
<h4 class="research-title">Weak Interactions</h4>
<p class="research-desc">Development of the V-A theory of the weak interaction with Murray Gell-Mann. This theory correctly predicted the structure of weak decays and was later incorporated into the electroweak unification by Weinberg, Salam, and Glashow.</p>
</div>
</div>

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
