---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About & Resume**

Hi! I'm **{{ site.author.name }}**,
a data scientist and physicist passionate about making science accessible.  <br> 
I'm looking to combine my skills in data science and my background in physics, in pursuit of a career in astronomy. <br> 
I love reading and playing video games--when I'm not digging through Python documentation for a project. 

<p class="text-center">
{% include elements/button.html link="../ELAM resume sept 2025.pdf" text="View Resume" %}
</p>

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>


<div class="row">
{% include about/timeline.html %}
</div>