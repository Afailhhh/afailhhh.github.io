---
layout: default
---

<h1 style="color:white; text-align:center; margin:2rem 0;">My GitHub Blog ✨</h1>
<ul style="list-style:none; max-width:800px; margin:0 auto; padding:0 20px;">
  {% for post in site.posts %}
    <li style="background:rgba(0,0,0,0.3); padding:1rem; margin:1rem 0; border-radius:8px;">
      <h2 style="margin:0; color:#ffd700;"><a href="{{ post.url }}" style="color:#ffd700; text-decoration:none;">{{ post.title }}</a></h2>
      <p style="color:white; margin:0.5rem 0 0 0;">{{ post.date | date: "%Y-%m-%d" }}</p>
    </li>
  {% endfor %}
</ul>
