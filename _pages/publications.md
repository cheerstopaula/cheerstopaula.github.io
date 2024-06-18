---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



Previous Publications
=== 

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my previous work on Tsunami Forecasting on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

