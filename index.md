---
layout: default
title: "Home"
---
Need to create a bibliography but having trouble doing so? You've come to the right place!
Simply navigate to the Bibliography Creator in the top right corner and input the information to get your formatted citations!

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
