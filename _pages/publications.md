---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

[C.4] <span style="color:blue">**[SOSP 24]**</span> *abc*.  
a, and bd.  
aaaa.  
[pdf](www.baidu.com){: .btn} [IEEE](www.baidu.com){: .btn}


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
