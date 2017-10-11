---
title: "Open Forcefield"
layout: archive
permalink: /members/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  #overlay_image: /assets/images/fuzzy-molecules-cropped.jpg
excerpt: "Open Forcefield Members"
---

{% for collection in site.collections %}
  {% if collection.label == "about_livecoms" %}
    {% for post in collection.docs %}
	  {% if post.layout != "archive" %}
        {% include archive-single.html %}
	  {% endif %}
    {% endfor %}
  {% endif %}
{% endfor %}
