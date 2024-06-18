---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Workshops and Poster Presentations
=== 

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Previous Publications
=== 

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my previous work on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

