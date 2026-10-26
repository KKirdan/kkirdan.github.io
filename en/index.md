---
layout: blog
title: "Kirdan"
lang: en
nav_id: 0
---
K. Kirdan is my pseudonym. My interests include reducing suffering, ethics, rationality, effective altruism, artificial intelligence, transhumanism, social justice and more.

Most of my writings are in Russian -- see my [personal blog](../blog/index.html) (started in 2019) and the [list](../index.html) of my other projects. See also [resources I recommend](../en/blog/links.html).

[Some of my posts](blog/index.html) are in English. Here are the most important ones:

<hr style="margin: 10px">

{% for post in site.posts %}
{% if post.lang=="en" and post.importance >= 7 %}
{% include post-entry.html title=post.title date=post.date meta=post.meta_tags lang='en' %}
{% endif %}
{% endfor %}

---

Contact me: <a href="mailto:{{ site.email }}">{{ site.email }}</a>
