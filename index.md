---
---

{% for post in site.pages %}
{% post.title %}: {% post.url %}
On {% post.date %} by {% post.author %}
{% post.excerpt %}
{% endfor %}