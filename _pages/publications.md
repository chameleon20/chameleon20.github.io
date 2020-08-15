---
title: "Publications"
permalink: /publications/
author_profile: false
---

For a complete list, visit my [Google Scholar](https://scholar.google.com/citations?user=evd0C28AAAAJ&hl=en) page.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

[Noise propagation in hybrid models of nonlinear systems: The Ginzburg-Landau equation](https://doi.org/10.1016/j.jcp.2014.01.015)
<b>S. Taverniers</b>, F.J. Alexander, and D.M. Tartakovsky.
