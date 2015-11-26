---
layout: page
title: About
permalink: /about/
---

<p class='about-paragraph'>Hello everyone and welcome to my blog. Let me introduce myself, my name is Damien Cosset. I'm French and I'm currently working on improving my skills as a Front-End Web developper. Outside of trying to break website, I enjoy video games, playing football and reading books. <br>
This blog was created with Jekyll and is hosted on github.<br>
Feel free to contact me if you want to chat!
Here are my contact infos: 

</p>

<ul class="social-media-about">
	<h4>My contact infos:</h4>
  <li class="email-info">
    <a href="mailto:{{ site.email }}">{{ site.email }}</a>
  </li>          
  {% if site.twitter_username %}
  <li>
    {% include icon-twitter.html username=site.twitter_username %}
  </li>
  {% endif %}
  
</ul>