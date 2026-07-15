---
layout: home
title: Pedro H. P. Rocha | Political Psychology and Communication
description: "Pedro H. P. Rocha is a Ph.D. candidate and Fulbright fellow at Texas Tech University specialized in the role of emotions in political communication."
---
## Bem-vindo!

<img src="{{ '/assets/headshot_2.jpeg' | relative_url }}" alt="Photo of Pedro H. P. Rocha" class="bio-headshot">

I am a [Ph.D. candidate](https://www.depts.ttu.edu/comc/faculty/faculty/procha.php) in the College of Media & Communication at Texas Tech University. I work under the supervision of [Dr. Bryan McLaughlin](https://www.depts.ttu.edu/comc/faculty/faculty/bmclaughlin.php).

My research currently examines the role of emotions in political communication, focusing on how people's expectations about how a conversation will feel shape their willingness to talk about politics. My doctoral work is jointly funded by the [Fulbright Program](https://fulbright.org.br/) and the [Brazilian Federal Agency for Support and Evaluation of Graduate Education](https://www.gov.br/capes/en), along with several scholarships from Texas Tech. 

Prior to moving West, I received a bachelor’s and a master’s degree in Communication from the [Federal University of Minas Gerais](http://www.ppgcom.fafich.ufmg.br/indexi.php), where I was affiliated with the [Image and Sociability](https://www.fafich.ufmg.br/gris/) and the [Media and Public Sphere](https://grupoemeblog.wordpress.com/) research groups. 

Outside of academia, I enjoy traveling to national parks and spending time in nature alongisde my fiancé and our little morkie, Diesel.

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
