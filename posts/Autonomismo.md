## ✍️ Últimos textos

{% for page in site.pages %}
  {% if page.path contains 'posts/' %}
- [{{ page.title | default: page.path }}]({{ page.url }})
  {% endif %}
{% endfor %}
