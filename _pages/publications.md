---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 1
---

---
## Interpretable Machine Learning
<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f {{site.scholar.bibliography}} %}

</div>

{% for paper in site.data[site.scholar.bibliography] %}
  ### {{ paper.title }}
  {% if paper.code %}
    Code: [Link]({{ paper.code }})
  {% endif %}
{% endfor %}

{% for paper in site.data[site.scholar.bibliography] %}
  ### {{ paper.title }}
  {% if paper.annotations %}
    <p>{{ paper.annotations }}</p>
  {% endif %}
{% endfor %}

{% for paper in site.data[site.scholar.bibliography] %}
  ### {{ paper.title }}
  {% if paper.annotations %}
    <p>{{ paper.annotations }}</p>
  {% endif %}
{% endfor %}


---
## Business Applications
<!-- _pages/publications.md -->
<div class="publications">

{% bibliography --file business %}

</div>