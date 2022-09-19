---
layout: archive
title: "Articles"
permalink: /publications/
author_profile: true
---


You can also find my articles on <u><a href="https://scholar.google.com/citations?user=-Jod_p4AAAAJ&hl=en">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.articles reversed %}
  {% include archive-single.html %}
{% endfor %}


{% if author.googlescholar %}
  {% You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u> %}
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
