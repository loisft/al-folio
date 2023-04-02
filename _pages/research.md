---
layout: page
permalink: /research/
title: research
description: a short list of (pre)publicated research works and projects 
years: [2022,2023]
nav: true
---

## preprints and publications

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

---

## talks 
### upcomming talks
- at the [Algebraic Geometry and Complex Geometry meeting](https://conferences.cirm-math.fr/2605.html), CIRM, end of Nov, 2022
- au [Séminaire de théorie des nombres](https://www.math.u-bordeaux.fr/imb/seminaire-theorie-des-nombres), Bordeaux, 9 décembre 2022

### past talks 
- *Comptage de courbes rationnelles de grand degré*, Séminaire de Théorie des Nombres de l’Institut Fourier, 16 juin 2022
- *Comportements asymptotiques de courbes rationnelles*, [Séminaire de l'équipe Géométrie du Laboratoire de Mathématiques de l'Université Savoie Mont Blanc (LAMA)](https://www.lama.univ-savoie.fr/index.php?use=seminaires&equipe=geometrie&lang=fr), 7 avril 2022 
- *Asymptotic behaviour of rational curves*, PhD Days, Institut Fourier, Oct. 27th, 2021
- *Rational curves : asymptotic behaviour of moduli spaces*, [Comprehensible seminar (séminaire des doctorants de l'Institut Fourier)](https://www-fourier.univ-grenoble-alpes.fr/~beratcl/semcompr.php), Dec. 10th, 2020

## additional stuff
Mon [mémoire de M2](/~faisantl/assets/pdf/FAISANT_MémoireRendu150620.pdf), réalisé en 2020 sous la direction d'Emmanuel Peyre.
