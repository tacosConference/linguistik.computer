---
layout: page
title: Schwestertagungen
---
{% for post in site.categories.conference %}
<article>
 <a {% if post.link %}href="{{ post.link }}"{% else %}href="{{ post.url }}"{% endif %}>
  <div class="featured-posts" {% if post.image %}style="background-image:url(/assets/img/{{ post.image }})"{% endif %}>
   <h2><span>{{ post.title }}</span></h2>
  </div>
 </a>
</article>
{% endfor %}