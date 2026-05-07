---
layout: default
title: Home
---

Hi! I'm a [Ph.D. candidate and Fulbright scholar](https://www.depts.ttu.edu/comc/faculty/faculty/procha.php) at the College of Media & Communication at Texas Tech University. I'm also a part-time instructor at CoMC, and teach courses about business and professional communication.

I'm interested in the diverse dynamics of communication in everyday politics, with a focus on interpersonal, mass-mediated, and platform-mediated interactions.

Currently, I'm working on projects that explore the emotional components influencing individuals' decisions to engage in or avoid discussing politics. My dissertation adviser is [Dr. Bryan McLaughlin](https://www.depts.ttu.edu/comc/faculty/faculty/bmclaughlin.php).

Before coming to Tech, I received a master's degree in the [Department of Social Communication](http://www.ppgcom.fafich.ufmg.br/index.php) at the [University of Minas Gerais](https://www.ufmg.br/international/about-the-ufmg/) in Belo Horizonte, Brazil. I have been affiliated with the [Research Group in Image and Sociability](https://www.fafich.ufmg.br/gris/) and the [Research Group in Media and Public Sphere](https://grupoemeblog.wordpress.com/) at the same institution.

[Google Scholar](https://scholar.google.com/citations?user=LBnOt9wAAAAJ&hl=en) · [ORCID](https://orcid.org/0000-0002-2762-9891) · [Lattes](http://lattes.cnpq.br/8720377365114820)

---

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
