---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

 **1) Multi-task learning of transcript isoform regulatory network** <br/>**Azim Dehghani Amirabad**, Marcel H. Schulz (in submission)
 
**2) Large-scale inference of competing endogeneous RNA networks with sparse partial correlation** <br/>Markus List, **Azim Dehghani Amirabad** , Dennis Kostka, Marcel H. Schulz
Bioinformatics (Proceedings of ISMB), 2019. ([full text](https://academic.oup.com/bioinformatics/article/35/14/i596/5529172)) 
 
**3) Multitask regression for context-specific prioritization of miRNA targets in transcripts** <br/>**Azim Dehghani Amirabad** , Marcel H. Schulz <br/>Proceedings of German Conference for Bioinformatics 2016 (full text) 
**4) Transgenic expression of the RNA binding protein IMP2 stabilizes miRNA targets in murine microsteatosis**<br/>**Azim Dehghani Amirabad** , Pathmanaban Ramasamy, Marina Wierz, Karl Nordström, Sonja M. Kessler, Marcel H. Schulz, Martin Simon<br/>Molecular Basis of Disease 2018 (full text) 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
