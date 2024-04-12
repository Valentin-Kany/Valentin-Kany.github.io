---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2024

**Computergestützte Bestimmung des Sprechflusses bei Vorschulkindern**<br>
*Valentin Kany and Jürgen Trouvain*<br>
Proc. 35th Conf. Elektronische Sprachsignalverarbeitung (ESSV '24), Regensburg, pp. 62-69
[Link Paper](https://www.coli.uni-saarland.de/~trouvain/docs/Kany_Trouvain_2024.pdf)<br>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
