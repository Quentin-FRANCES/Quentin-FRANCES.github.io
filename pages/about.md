---
layout: page
title: About
permalink: /about/
weight: 3
---

# **A propos de moi**

Bonjour, je suis **{{ site.author.name }}** :wave:,<br>
Je suis élève-ingénieur en 4ème année à l'INSA Rennes, spécialisé en électronique et informatique industrielle. J'aime concevoir des systèmes embarqués, du schéma jusqu'au firmware, en passant par la conception du PCB. Ce portfolio regroupe mes projets personnels et académiques.
**[Cliquez ICI pour voir mon CV !](/assets/CV_FRANCES_Quentin.pdf)**

<div class="row">
{% include about/skills.html title="Software Skills" source=site.data.software-skills %}
{% include about/skills.html title="Hardware Skills" source=site.data.hardware-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>