---
layout: default
---

# $ cat posts.txt
{:id="posts"}

---
{% for post in site.posts %}

<h2><a href="{{ post.url | prepend:site.baseurl }}" title="{{ post.description }}">{{ post.title }}</a></h2>

{% endfor %}
</ul>
