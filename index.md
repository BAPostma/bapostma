---
---

{% for post in site.posts %}
## [{% post.title %}]({% post.url %})
_On {% post.date %} by {% post.author %}_
> {% post.excerpt %}


{% endfor %}