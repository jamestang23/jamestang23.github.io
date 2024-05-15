---
layout: archive
title: "Publications"
permalink: /publications
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Check our recent publications in <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
