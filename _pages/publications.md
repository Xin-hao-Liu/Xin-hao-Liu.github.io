---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

---
layout: archive
title: "Working Paper"
permalink: /publications/
author_profile: true
---
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
