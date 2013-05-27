---

layout: default

---


{% for post in site.posts %}
  {{ post.content | truncatewords: 400 }}  
  <a href="{{ post.url }}"> continue </a>
{% endfor %}