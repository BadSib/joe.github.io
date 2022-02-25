---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**[J]** Journal, **[C]** Conference, **[W]** Workshop, **[P]** Poster, **[D]** Demo, **[B]** Book, **[I]** Invited Talk, and **[N]** None peer-reviewed. For the publication list including Japanese litarature, please refer to the above link, **日本語**.
{: .notice}

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
