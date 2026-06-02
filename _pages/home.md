---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<h2 class="home-hero">{{ site.name }}</h2>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}</p>

<div class="chip-container" markdown="0">
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Performance-Based Earthquake Engineering</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Generative Models for Structural Design</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Intensity Measure Selection</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Active Learning & UQ</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">PT-CLT Rocking Wall Systems</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Reliability-Based Optimization</a>
</div>

Theoretical physics...

<div class="callout callout-success" markdown="0">
<div class="callout-title"><i class="fa-solid fa-award callout-icon"></i> Nobel Prize in Physics, 1965</div>
<p>Awarded the Nobel Prize jointly with Julian Schwinger and Shin'ichiro Tomonaga for fundamental work in quantum electrodynamics, with deep-ploughing consequences for the physics of elementary particles.</p>
</div>

<div class="banner-frame" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}/images/banner.jpg" alt="Feynman diagrams" loading="lazy">
<div class="banner-caption">Examples of Feynman diagrams. Feynman R., <em>The theory of positrons. Phys. Rev.</em> (1949)</div>
</div>

### About me

I am a PhD researcher at Penn State working at the intersection of earthquake engineering, machine learning, and uncertainty quantification. My work focuses on developing probabilistic and information-driven methods for seismic performance assessment and structural design within the PBEE framework.

I am particularly interested in how generative models and active learning can improve efficiency and robustness in structural engineering workflows. My main application is post-tensioned cross-laminated timber (PT-CLT) rocking wall systems modeled in OpenSeesPy.
