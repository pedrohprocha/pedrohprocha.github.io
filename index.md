---
layout: default
title: Home
description: "Pedro H. P. Rocha is a Ph.D. candidate and Fulbright fellow at Texas Tech University."
---
*Bem-vindo* to my website!
<br>
I'm a [doctoral candidate](https://www.depts.ttu.edu/comc/faculty/faculty/procha.php) at the College of Media & Communication at Texas Tech University, currently working on research that explores how emotions can motivate people to engage in political conversations.

My doctoral work is funded by the [Fulbright Program](https://fulbright.org.br/), [the Brazilian government](https://www.gov.br/capes/en), and Texas Tech University. My advisor is [Dr. Bryan McLaughlin](https://www.depts.ttu.edu/comc/faculty/faculty/bmclaughlin.php).

I was born and raised in Brazil, where I studied at the [University of Minas Gerais](https://www.ufmg.br/international/about-the-ufmg/). Outside of academia, I enjoy watching movies and hiking with my partner and our little morky.

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

<p style="text-align: center;"><span class="text-rust"><strong>✵ &nbsp; ✵ &nbsp; ✵</strong></span></p>
