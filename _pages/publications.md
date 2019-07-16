---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

 **1) Multi-task learning of transcript isoform regulatory network**
**Azim Dehghani Amirabad**, Marcel H. Schulz (in submission)
 
**2) Large-scale inference of competing endogeneous RNA networks with sparse partial correlation**
Markus List, **Azim Dehghani Amirabad** , Dennis Kostka, Marcel H. Schulz
Bioinformatics (Proceedings of ISMB), 2019. ([full text](https://academic.oup.com/bioinformatics/article/35/14/i596/5529172)) 
 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
