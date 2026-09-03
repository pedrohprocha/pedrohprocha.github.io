---
layout: home
title: Pedro H. P. Rocha | Political Psychology and Communication
description: "Pedro H. P. Rocha is a Ph.D. candidate and Fulbright fellow at Texas Tech University specialized in the role of emotions in political communication."
---
## Bem-vindo!

<img src="{{ '/assets/headshot_2.jpeg' | relative_url }}" alt="Photo of Pedro H. P. Rocha" class="bio-headshot">

I am a [Ph.D. candidate](https://www.depts.ttu.edu/comc/faculty/faculty/procha.php) and Fulbright fellow at the Texas Tech University College of Media & Communication.

My work is jointly funded by a award from the [Fulbright Program](https://fulbright.org.br/) and the [Ministry of Education of Brazil](https://www.gov.br/capes/en), and my dissertation is being supervised by [Dr. Bryan McLaughlin](https://www.depts.ttu.edu/comc/faculty/faculty/bmclaughlin.php).

My research revolves around the different roles media and communication plays in everyday politics, and I employ quantitative and qualitative methods in my inquiries. Currently, I am investigating the role of people's expectations about their future emotional states (i.e., [affective forecasting](https://dictionary.apa.org/affective-forecasting)) on their motivations to talk politics with others.

Prior to moving West, I received a bachelor’s and a master’s degree in Communication from the [Federal University of Minas Gerais, Brazil](http://www.ppgcom.fafich.ufmg.br/indexi.php), where I collaborated in the [Image and Sociability](https://www.fafich.ufmg.br/gris/) and the [Media and Public Sphere](https://grupoemeblog.wordpress.com/) research groups. 

When I'm not working, I enjoy traveling to national parks and spending time in nature with my fiancé and our little morkie, <a href="{{ '/assets/diesel.jpeg' | relative_url }}">Diesel</a>.

## Recent Publications

<div class="pub-list-home">
{% for pub in site.data.publications.peer_reviewed limit:2 %}
<div class="pub-item">
  <span class="pub-num">☛</span>
  <div class="pub-content">
    <p class="pub-title">{% if pub.doi %}<a href="{{ pub.doi }}">{{ pub.title }}</a>{% else %}{{ pub.title }}{% endif %}</p>
    <p class="pub-meta">{{ pub.authors }}. Available at <em>{{ pub.venue }}</em>.</p>
  </div>
</div>
{% endfor %}
</div>

<p style="text-align: center;"><span class="text-rust"><strong>✵ &nbsp; ✵ &nbsp; ✵</strong></span></p>
