---
layout: default
---

# What I Read

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %d, %Y" }}*

{{ post.content }}

---
{% endfor %}
