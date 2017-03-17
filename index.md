---
---

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
_On {{ post.date | date_to_long_string }} by {{ post.author }}_
> {{ post.excerpt }}

_[Read more...]({{ post.url }})_
{% endfor %}