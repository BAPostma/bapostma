---
---

{% for post in site.pages %}
## [
   {% post.title %} 
](
   {% post.url %} 
)
_On {% post.date %} by {% post.author %}_
> {% post.excerpt %}


{% endfor %}