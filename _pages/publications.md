---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For the most updated list of my publications, please visit my [Google Scholar]() page.

## Journal articles (* indicates working and under review papers)

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
