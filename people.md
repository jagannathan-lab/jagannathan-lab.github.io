---
layout: default
title: People
---

{% for person in site.people %}


<a href="{{ person.url | prepend: site.baseurl }}">
        <h2>{{ people.title }}</h2>
</a>

<p class="post-excerpt">{{ people.description | truncate: 160 }}</p>

{% endfor %}      
