---
layout: page
title: Abstracts
permalink: /abstracts/
---

{% for abstract in site.abstracts %}
  <h2>{{ abstract.theme }}</h2>
  **{{ abstract.title }}**
  <p>{{ abstract.content | markdownify }}</p>
<br>
Sample presentations:
{% if abstract.conf1 %}> {{abstract.conf1}}{% endif %}{% if abstract.conf1_pair contains " " %} - with {{ abstract.conf1_pair }} {% endif %}
{% if abstract.conf2 %}>{% endif %}
{% if abstract.conf2 %}> {{abstract.conf2}}{% endif %}{% if abstract.conf2_pair contains " " %} - with {{ abstract.conf2_pair }} {% endif %}
{% if abstract.conf3 %}>{% endif %}
{% if abstract.conf3 %}> {{abstract.conf3}}{% endif %}{% if abstract.conf3_pair contains " " %} - with {{ abstract.conf3_pair }} {% endif %}
<br>

<!--
  Sample recording from <a href="{{ abstract.confLink }}">{{ abstract.confName }}</a>
  {% if abstract.confPair contains " " %} -- with {{ abstract.confPair }} {% endif %}
  {% include youtubePlayer.html id=abstract.confVideo %}
-->

{% endfor %}