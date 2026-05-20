---
layout: default
title: Home
description: "Pedro H. P. Rocha is a Ph.D. candidate and Fulbright fellow at Texas Tech University studying political communication."
---

Hi! I'm a [doctoral candidate](https://www.depts.ttu.edu/comc/faculty/faculty/procha.php) at the College of Media & Communication at Texas Tech University.

I'm currently working on projects that examine how people anticipate and navigate political conversations in divided societies, and my advisor is [Dr. Bryan McLaughlin](https://www.depts.ttu.edu/comc/faculty/faculty/bmclaughlin.php). My doctoral work is funded by the [Fulbright Program](https://fulbright.org.br/), [the Brazilian government](https://www.gov.br/capes/en), and Texas Tech University. 

I was born and raised in Brazil, where I studied at the [University of Minas Gerais](https://www.ufmg.br/international/about-the-ufmg/). Outside of academia, I enjoy watching movies and hiking with my partner and our dog, Diesel.

## ☛ Recent Publications

<div class="pub-list-home">
{% for pub in site.data.publications.peer_reviewed limit:2 %}
<div class="pub-item">
  <p class="pub-title">{% if pub.doi %}<a href="{{ pub.doi }}">{{ pub.title }}</a>{% else %}{{ pub.title }}{% endif %}</p>
  <p class="pub-authors">{{ pub.authors }}</p>
  <p class="pub-venue">{{ pub.venue }}</p>
  <div class="pub-links">
  </div>
</div>
{% endfor %}
</div>
