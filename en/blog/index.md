---
layout: blog
title: "Blog"
lang: en
nav_id: 1
---
<div class="posts">
  <h2>Most important:</h2>
  {% for post in site.posts %}
    {% if 7 <= post.importance and post.importance <= 10 and post.lang=='en' %}{% unless post.meta_tags contains "личное" %}
      {% include post-entry.html title=post.title date=post.date meta=post.meta_tags lang='en' %}
    {% endunless %}{% endif %}
  {% endfor %}
  <hr>
  <h2>Less important:</h2>
  {% for post in site.posts %}
    {% if 4 <= post.importance and post.importance <= 6 and post.lang=='en' %}{% unless post.meta_tags contains "личное" %}
      {% include post-entry.html title=post.title date=post.date meta=post.meta_tags lang='en' %}
    {% endunless %}{% endif %}
  {% endfor %}
  <hr>
  <h2>Personal:</h2>
  {% for post in site.posts %}
    {% if post.meta_tags contains "личное" and post.lang=='en' %}
	  {% include post-entry.html title=post.title date=post.date meta=post.meta_tags lang='en' %}
    {% endif %}
  {% endfor %}
  <hr>
  <h2>Other:</h2>
  {% for post in site.posts %}
    {% if 1 <= post.importance and post.importance <= 3 and post.lang=='en' %}{% unless post.meta_tags contains "личное" %}
      {% include post-entry.html title=post.title date=post.date meta=post.meta_tags lang='en' %}
    {% endunless %}{% endif %}
  {% endfor %}
</div>
