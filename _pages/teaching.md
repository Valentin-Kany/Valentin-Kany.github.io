---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

## Summer semester 2024

**Seminar [“Introduction to Phonetics and Phonology”](https://www.coli.uni-saarland.de/courses/einf_phon_phon/2024_SS/phonphon.html){:target="_blank"}**<br>

**Forschungskolloquium DaF/DaZ**<br>

## Summer semester 2023

**Seminar "Einführung in die statistische Auswertung und Konzipierung von Studien mit Fokus DaF/DaZ"**<br>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}