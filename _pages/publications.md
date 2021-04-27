---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p class="notice"><strong>[J]</strong> Journal, <strong>[C]</strong> Conference, <strong>[P]</strong> Poster, <strong>[D]</strong> Demo, <strong>[B]</strong> Book, <strong>[I]</strong> Invited Talk, and <strong>[N]</strong> None peer-reviewed. For the publication list including Japanese litarature, please refer to the above link, <strong>日本語</strong>.</p>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
