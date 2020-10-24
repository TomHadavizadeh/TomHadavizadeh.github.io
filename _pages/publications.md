---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.inspirehep %}
  You can also find my full list of articles on <u><a href="{{author.inspirehep}}">inspirehep</a>.</u>
{% endif %}

You can also find my full list of articles on <u><a href="{{author.inspirehep}}">inspirehep</a> {{author.inspirehep}} .</u>

{% include base_path %}

### Notable journal publications 
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Public notes 


### Conference proceedings 

