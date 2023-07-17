---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

ℹ️ The full list of publications is available on [Google Scholar](https://scholar.google.com/citations?user=RPoZ-I8AAAAJ&hl=en) or [here](../_pages/Yuelin_CV.pdf).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
