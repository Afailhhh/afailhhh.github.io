---
layout: default
---

# Welcome to My Blog ✨

## Recent Posts
{% for post in site.posts %}
- {{ post.date | date: "%Y-%m-%d" }}: [{{ post.title }}]({{ post.url }})
{% endfor %}