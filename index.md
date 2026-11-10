---
layout: home
title: Pedro H. P. Rocha | Interpersonal Political Communication
description: "Pedro H. P. Rocha is a Ph.D. candidate and Fulbright fellow at Texas Tech University specialized in the role of emotions in interpersonal political communication."
---
<div class="intro" markdown="1">

<img src="{{ '/assets/headshot_2.jpeg' | relative_url }}" alt="Photo of Pedro H. P. Rocha" class="bio-headshot">

{% include profile-links.html %}

<div class="intro-text" markdown="1">

I am a Ph.D. candidate and Fulbright fellow at the Texas Tech University College of Media & Communication. My dissertation advisor is [Dr. Bryan McLaughlin](https://www.depts.ttu.edu/comc/faculty/faculty/bmclaughlin.php), and my doctoral work has been funded by a binational award from the [U.S. Department of State](https://fulbright.org.br/) and the [Brazilian Agency for Support and Evaluation of Graduate Education (CAPES)](https://www.gov.br/capes/en).

I study the different roles media and communication play in everyday politics, and use an array of quantitative and qualitative methods to investigate contemporary political communication phenomena. Currently, I am focused on understanding how people's expectations about their future emotional states (i.e., [affective forecasting](https://dictionary.apa.org/affective-forecasting)) shape their motivations to discuss politics with others.

Prior to moving West, I received a B.A. in Journalism and an M.A. in Social Communication from the [Federal University of Minas Gerais](http://www.ppgcom.fafich.ufmg.br/indexi.php) in Brazil, where I worked as a research assistant in the [Image and Sociability (GRIS)](https://www.fafich.ufmg.br/gris/) and the [Media and Public Sphere (EME)](https://grupoemeblog.wordpress.com/) research groups. 

When I'm not working, I enjoy hiking, birding, and traveling to as many national parks as possible with my partner and our little morkie, <a href="{{ '/assets/diesel.jpeg' | relative_url }}">Diesel</a>.

</div>
</div>

## Recent Publications

<div class="pub-list-home">
{% for pub in site.data.publications.peer_reviewed limit:2 %}
<div class="pub-item">
  <span class="pub-num">☞</span>
  <div class="pub-content">
    <p class="pub-title">{% if pub.doi %}<a href="{{ pub.doi }}">{{ pub.title }}</a>{% else %}{{ pub.title }}{% endif %}</p>
    <p class="pub-meta">{{ pub.authors }}. Available at <em>{{ pub.venue }}</em>.</p>
  </div>
</div>
{% endfor %}
</div>
