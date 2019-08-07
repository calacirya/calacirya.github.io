---
title: Calacirya
layout: default
permalink: /posts
---

## Posts

{% assign posts = site.posts | join: '' %}
{% if posts != '' %}
{% assign posts = site.posts | order: 'date' %}
{% for post in posts %}
### [{{ post.title }}]({{ post.url }})
By {{ post.author }}, published {{ post.date | date: site.date_format }}.

> {{ post.excerpt }}

{% assign last = posts | last %}{% unless post == last %}---{% endunless %}
{% endfor %}
{% else %}
Sorry! :cry:

There are no posts right now. Come back soon and we'll try and fix it!

Please also feel free to [open a request]({{ site.github.issues_url }}) at our [repository]({{ site.github.repository_url }})!
{% endif %}
