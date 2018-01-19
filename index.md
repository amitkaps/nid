---
layout: default
---

## Jan 2018: Notes

<div class="grid">
{% for project in site.data.nid %}
    <a class="grid-item" href="https://{{ project.github }}.github.io/{{ project.notes_project }}">
      <img src="https://{{ project.github}}.github.io/{{ project.notes_project }}/thumbnail.png">
      <h3 class="name"> {{ project.name }} </h3>
      <p class="github"> <small>@{{ project.github }} </small> </p>
    </a>
{% endfor %}
</div>