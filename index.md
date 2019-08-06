---
layout: default
---

## Welcome to the home page of {{ site.title }}!

{{ site.title }} is a project aiming to embark some more robust projects from [Nereare](https://github.com/Nereare).

## {{ site.title }} Projects
{% for project in site.github.public_repositories | sort: "name" %}
{% unless project.private %}
 * **[{{ project.name }}]({{ project.html_url }}):** {{ project.description }} Distributed under the [{{ project.license.name }}]({{ project.license.url }}).
{% endunless %}
{% endfor %}

## Members
<div class="member">
{% for member in site.github.organization_members | uniq | sort: "login" %}
<a href="{{ member.html_url }}">
  <img alt="{{ member.login }}'s avatar" src="{{ member.avatar_url }}" />
  <p>{{ member.login }}</p>
</a>
{% endfor %}
</div>
