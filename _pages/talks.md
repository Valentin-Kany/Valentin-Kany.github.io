---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

## 2024

**Semiautomatic support of speech fluency assessment by detecting filler particles and determining speech tempo**<br>
*Valentin Kany and Jürgen Trouvain*<br>
20th Conf. Phonetik & Phonologie (P&P '24), Halle (Saale).

**Semiautomatic support of speech fluency assessment by detecting filler particles 
and determining speech tempo**<br>
*Valentin Kany and Jürgen Trouvain*<br>
Workshop "Prosodic features of language learners", Leiden.

**A usage-based approach to measuring success in language learning**<br>
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
