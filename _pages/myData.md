---
layout: archive
title: "Data"
permalink: /myData/
author_profile: true
---

Here is a list of large datasets I have published worked on published.

All are freely available in the original, raw data. Code for analyses are available on [github](https://github.com/atomadam2)

{% include base_path %}

{% for post in site.myData reversed %}
  {% include archive-single.html %}
{% endfor %}
