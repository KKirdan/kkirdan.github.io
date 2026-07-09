---
layout: blog
title: "Kirdan"
lang: en
nav_id: 0
---
Hi, my name's K. Kirdan.

My interests include reducing suffering, ethics, rationality, effective altruism, artificial intelligence, transhumanism, social justice and more.

Most of my writings are in Russian -- see my [personal blog](../blog/index.html) (started in 2019) and the [list](../index.html) of my other projects. See also [resources I recommend](../en/blog/links.html).

<hr style="margin: 10px">

{% for post in site.posts %}
{% if post.lang=="en" %}
{% include post-entry.html title=post.title date=post.date tags=post.tags meta=post.meta_tags %}
{% endif %}
{% endfor %}

<hr style="margin: 10px">

Contact me: <a href="mailto:{{ site.email }}">{{ site.email }}</a>
