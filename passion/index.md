---
layout: default
title: Domov
permalink: /passion
---

# Záujmy


## Cyklistika

Cyklistika patrí medzi moje obľúbené aktivity. Je to najefektívnejší prenos hmoty z bodu A do bodu B, pričom energiu odovzdáva výlučne iba človek samotný.

<div>
{% for f in site.static_files %}
  {% if f.path contains '/assets/img/cycling' %}
  <img class="md-image" src="{{ f.path }}"/>
  {% endif %}
{% endfor %}
</div>


## Pozeranie serialov
Medzi moje najobľúbenejšie seriály patrí, respektíve patril seriál Breaking Bad. Patril, pretože som ho úspešne a bohužiaľ dopozeral. Bol asi najlepší serial, ktorý som doposiaľ videl. Ďalším seriálom je serial Dexter, ktorý som taktiež zakončil ôsmov sériou. Momentálne som začal pozerať seriál Kravaťáci, ale pre časovú nedostatočnosť ho budem musieť posunúť na letné prázdniny.

<div>
{% for f in site.static_files %}
  {% if f.path contains '/assets/img/serialy' %}
  <img class="md-image" src="{{ f.path }}"/>
  {% endif %}
{% endfor %}
</div>

## Fotografie

Celkom ma baví fotenie scenérií ako západy slnka. Východ slnka sa mi bohužiaľ ešte nepodarilo odfotografovať, pretože môj programátorský režim s názvom "Ísť spať o tretej ráno" mi to doposiaľ nedovolil.

<div>
{% for f in site.static_files %}
  {% if f.path contains '/assets/img/photography' %}
  <img class="md-image" src="{{ f.path }}"/>
  {% endif %}
{% endfor %}
</div>
