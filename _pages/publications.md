---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## 2026

**Automatic Prediction of Child Speech Fluency with Game-Based Data from German Preschoolers**<br>
*Valentin Kany, Bernd Möbius, and Jürgen Trouvain*<br>
Proc. 15th Language Resources and Evaluation Conference (LREC '26), Palma de Mallorca, pp. 5607-5616.
[[pdf]](http://www.lrec-conf.org/proceedings/lrec2026/pdf/2026.lrec2026-1.439.pdf){:target="_blank"} [[poster]](/files/Poster_SpeechScience_Kany_2702.pdf){:target="_blank"} <br>

**Automatic Detection of Disfluencies in L1 and L2 Child Speech**<br>
*Martha Schubert and Valentin Kany*<br>
Proc. 37th Conf. Elektronische Sprachsignalverarbeitung (ESSV '26), Eichstätt, pp. 208-215.
[[pdf]](https://www.essv.de/pdf/2026_208_215.pdf){:target="_blank"} [[poster]](/files/Poster_SpeechScience_Kany_2702.pdf){:target="_blank"} <br>

## 2025

**From Features to Fluency: Predicting Perceived Speech Fluency of Preschool Children for Language Proficiency Assessments** <br>
*Valentin Kany* <br>
Proc. 10th Workshop on Speech and Language Technology in Education (SLaTE '25), Nijmegen, pp. 118-122.
[[pdf]](https://www.isca-archive.org/slate_2025/kany25_slate.pdf){:target="_blank"} [[poster]](/files/Poster_Kany_2025.pdf){:target="_blank"} <br>

**Annotation of disfluencies in child speech**<br>
*Valentin Kany and Jürgen Trouvain*<br>
Proc. 36th Conf. Elektronische Sprachsignalverarbeitung (ESSV '25), Halle (Saale), pp. 247-254.
[[pdf]](/files/Kany_Trouvain_2025.pdf){:target="_blank"} [[poster]](/files/Poster_Kany_Trouvain_2025.pdf){:target="_blank"}
Best Student Paper Award <br>

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
