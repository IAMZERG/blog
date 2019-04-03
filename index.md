---
layout: default
author: Wes
---

# $ cat posts.txt
{:id="posts"}

---
{% for post in site.posts %}

<h2>{{ post.title }} :: <a href="{{ post.url | prepend:site.baseurl }}" title="{{ post.description }}">en</a></h2>

{% endfor %}
</ul>
