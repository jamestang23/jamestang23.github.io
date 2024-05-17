---
layout: archive
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  Check our recent publications in [Google Scholar](https://scholar.google.com/citations?user=-5bbqWsAAAAJ&hl=en).
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
