---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

(*: Equal Contribution)

{% if author.googlescholar %}
  For a more complete list, please refer to <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
