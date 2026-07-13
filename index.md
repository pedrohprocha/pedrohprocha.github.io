---
layout: home
title: Home
description: "Pedro H. P. Rocha is a Ph.D. candidate and Fulbright fellow at Texas Tech University."
---
## Bem-vindo!

I am a [Ph.D. candidate](https://www.depts.ttu.edu/comc/faculty/faculty/procha.php) in the College of Media & Communication at Texas Tech University. My research examines the role of emotions in political communication, focusing on how people's expectations about how a conversation will feel shape their willingness to talk about politics.

My doctoral work is jointly funded by the [Fulbright Program](https://fulbright.org.br/) and the [Brazilian Federal Agency for Support and Evaluation of Graduate Education](https://www.gov.br/capes/en), along with several scholarships from Texas Tech. I work under the supervision of [Dr. Bryan McLaughlin](https://www.depts.ttu.edu/comc/faculty/faculty/bmclaughlin.php).

I was born and raised in Brazil, where I was awarded degrees at the [Federal University of Minas Gerais](https://www.ufmg.br/international/about-the-ufmg/). Outside of academia, I enjoy traveling and spending time in nature alongisde my partner and our little morkie, Diesel.

## Recent Publications

<div class="pub-list-home">
{% for pub in site.data.publications.peer_reviewed limit:2 %}
<div class="pub-item">
  <span class="pub-num">☛</span>
  <div class="pub-content">
    <p class="pub-title">{% if pub.doi %}<a href="{{ pub.doi }}">{{ pub.title }}</a>{% else %}{{ pub.title }}{% endif %}</p>
    <p class="pub-meta">{{ pub.authors }} 𐫱 <em>{{ pub.venue }}</em>.</p>
  </div>
</div>
{% endfor %}
</div>

<p style="text-align: center;"><span class="text-rust"><strong>✵ &nbsp; ✵ &nbsp; ✵</strong></span></p>
