---
layout: home
title: Pedro H. P. Rocha | Political Psychology and Communication
description: "Pedro H. P. Rocha is a Ph.D. candidate and Fulbright fellow at Texas Tech University specialized in the role of emotions in political communication."
---
<div class="intro" markdown="1">

<img src="{{ '/assets/headshot_2.jpeg' | relative_url }}" alt="Photo of Pedro H. P. Rocha" class="bio-headshot">

{% include profile-links.html %}

<div class="intro-text" markdown="1">

I am a Ph.D. candidate and Fulbright fellow at the Texas Tech University College of Media & Communication. My dissertation is being supervised by [Dr. Bryan McLaughlin](https://www.depts.ttu.edu/comc/faculty/faculty/bmclaughlin.php), and my doctoral work has been funded by a binational award from the [Fulbright Program](https://fulbright.org.br/) (U.S. Department of State) and the [Federal Agency for Support and Evaluation of Graduate Education](https://www.gov.br/capes/en) (Brazilian Ministry of Education).

I'm interested in the different roles media and communication play in everyday politics, and often employ quantitative and qualitative methods in my inquiries. Currently, I am investigating how people's expectations about their future emotional states (i.e., [affective forecasting](https://dictionary.apa.org/affective-forecasting)) affect their motivations to talk politics with others.

Prior to moving West, I received a bachelor’s in Journalism and a master’s in Social Communication from the [Federal University of Minas Gerais, Brazil](http://www.ppgcom.fafich.ufmg.br/indexi.php), where I worked as a research assistant in the [Image and Sociability](https://www.fafich.ufmg.br/gris/) and the [Media and Public Sphere](https://grupoemeblog.wordpress.com/) research groups. 

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
