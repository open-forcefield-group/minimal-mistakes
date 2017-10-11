---
title: "Open Forcefield Group"
layout: archive
permalink: /about/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  #overlay_image: /assets/images/livecoms-splash.jpg
excerpt: "About Open Forcefield"
---

{% for collection in site.collections %}
  {% if collection.label == "about_open_forcefield" %}
    {% for post in collection.docs %}
	  {% if post.layout != "archive" %}
        {% include archive-single.html %}
	  {% endif %}
    {% endfor %}
  {% endif %}
{% endfor %}
