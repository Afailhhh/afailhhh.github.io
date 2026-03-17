---
layout: default
---

# My GitHub Blog ✨

{% for post in site.posts %}
- {{ post.title }}
  {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
