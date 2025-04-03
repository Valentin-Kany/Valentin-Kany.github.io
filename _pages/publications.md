---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2025

**Annotation of disfluencies in child speech**<br>
*Valentin Kany and Jürgen Trouvain*<br>
Proc. 36th Conf. Elektronische Sprachsignalverarbeitung (ESSV '25), Halle, pp. 247-254.
[[pdf]](/files/Kany_Trouvain_2025.pdf){:target="_blank"} [[poster]](https://www.coli.uni-saarland.de/~trouvain/docs/Kany_Trouvain_2024.pdf){:target="_blank"} <br>

## 2024

**Computergestützte Bestimmung des Sprechflusses bei Vorschulkindern**<br>
*Valentin Kany and Jürgen Trouvain*<br>
Proc. 35th Conf. Elektronische Sprachsignalverarbeitung (ESSV '24), Regensburg, pp. 62-69.
[[pdf]](https://www.coli.uni-saarland.de/~trouvain/docs/Kany_Trouvain_2024.pdf){:target="_blank"}<br>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
