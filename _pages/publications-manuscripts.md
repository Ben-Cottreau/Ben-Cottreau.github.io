---
layout: archive
title: "Journal Articles"
permalink: /publications/manuscripts/
author_profile: true
---
{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.category == "journals" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
