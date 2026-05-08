---
layout: default
title: Home
---

Hi! I'm a [Ph.D. candidate](https://www.depts.ttu.edu/comc/faculty/faculty/procha.php) and [Fulbright scholar from Brazil](https://fulbright.org.br/) at the College of Media & Communication at Texas Tech University. I'm currently working on projects that examine how people anticipate and navigate political conversations in divided societies. My dissertation advisor is [Dr. Bryan McLaughlin](https://www.depts.ttu.edu/comc/faculty/faculty/bmclaughlin.php).

Before coming to Tech, I received an M.A. and a B.A. from the [Department of Social Communication](http://www.ppgcom.fafich.ufmg.br/index.php) at the [University of Minas Gerais](https://www.ufmg.br/international/about-the-ufmg/) in Belo Horizonte, Brazil. While there, I conducted research at the [Research Group in Image and Sociability](https://www.fafich.ufmg.br/gris/) and the [Research Group in Media and Public Sphere](https://grupoemeblog.wordpress.com/).

Outside of academia, I enjoy going to concerts, watching movies, gardening my indoor plants, and hiking with my partner and our dog, Diesel.

## Recent Publications

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
