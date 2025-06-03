---
layout: default
title: Thiago Araújo — Escritos
---

# 👋 Bem-vindo

Este é meu espaço pessoal de escrita — onde compartilho ideias, reflexões e textos autorais sobre filosofia, liberdade e autonomia.

> “A liberdade começa quando termina o automatismo.” — Autonomismo

---

## ✍️ Últimos textos

{% for post in site.pages %}
  {% if post.path contains 'posts/' %}
- [{{ post.title | default: post.path }}]({{ post.url }})
  {% endif %}
{% endfor %}

---

## 📚 Sobre este projeto

Este site foi criado com:

- Markdown puro `.md`
- [GitHub Pages](https://pages.github.com/)
- Tema: [Cayman](https://github.com/pages-themes/cayman)

---

## 📬 Contato

- Instagram: [@seuperfil](https://instagram.com/seuperfil)
- Email: seuemail@example.com