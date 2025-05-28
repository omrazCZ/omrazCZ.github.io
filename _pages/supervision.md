---
layout: archive
title: "Supervision"
permalink: /supervision/
author_profile: true
---

<div class="wordwrap">Throughout my research career, I have supervised MSc and BSc students in the following projects:</div>

{% include base_path %}

{% for post in site.supervision reversed %}
  {% include archive-single.html %}
{% endfor %}
