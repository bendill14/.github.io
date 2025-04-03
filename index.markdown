---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<h3>Mes Projets GitHub</h3>
<ul>
  {% for repo in site.data.repositories %}
    <li>
      <a href="{{ repo.url }}">{{ repo.name }}</a> - {{ repo.description }}
    </li>
  {% endfor %}
</ul>
