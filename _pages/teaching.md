---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

##Summer semester 2024

**Seminar [“Introduction to Phonetics and Phonology”](https://www.coli.uni-saarland.de/courses/einf_phon_phon/2024_SS/phonphon.html){:target="_blank"}**<br>
*Stefanie Haberzettl, Valentin Kany and Nicole Weidinger*<br>
4th Conf. Constructionist Approaches to Language Pedagogy (CALP4), Erlangen.

**Computer-aided assessment of speech fluency of preschool children**<br>
*Valentin Kany and Jürgen Trouvain*<br>
35th Conf. Elektronische Sprachsignalverarbeitung (ESSV '24), Regensburg.

## 2023

**Kommissar Wuschel - Sprachstandsdiagnose bei Vorschulkindern durch ein Serious Game**<br>
*Valentin Kany*<br>
Linguistischer Nachwuchsworkshop (LiNaWo 2023), Warsaw.

**Preschool language assessment for multilingual children. A usage-based approach**<br>
*Nicole Weidinger, Stefanie Haberzettl and Valentin Kany*<br>
16th International Cognitive Linguistics Conference (ICLC16), Düsseldorf.


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
