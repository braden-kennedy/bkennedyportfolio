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
