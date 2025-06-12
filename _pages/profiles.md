---
layout: page
permalink: /people/
title: people
description: people who have partnered with me in previous projects as well as those currently collaborating
nav: true
nav_order: 7
display_categories: [Project Collaborators, Academic Co-authors]
horizontal: false
---

{% assign projects = 
  [
    {
      "title": "Dr. Manika Lamba",
      "category": "Project Collaborators",
      "affiliation": "University of Oklahoma",
      "image": "/assets/images/people/manika.jpg"
    },
    {
      "title": "Crissandra George",
      "category": "Project Collaborators",
      "affiliation": "Case Western Reserve University",
      "image": "/assets/images/people/crissandra.jpg"
    },
    {
      "title": "Yujia Wei",
      "category": "Project Collaborators",
      "affiliation": "University of Illinois Urbana-Champaign",
      "image": "/assets/images/people/olivia.png"
    },
    {
      "title": "Hewei Tang",
      "category": "Project Collaborators",
      "affiliation": "University of Illinois Urbana-Champaign",
      "image": "/assets/images/people/henry.jpg"
    },
    {
      "title": "Tam Le",
      "category": "Project Collaborators",
      "affiliation": "University of Oklahoma",
      "image": "/assets/images/people/tam.jpg"
    },
    {
      "title": "Mochammad Riski Destrianto",
      "category": "Project Collaborators",
      "affiliation": "Politeknik Negeri Semarang",
      "image": "/assets/images/people/riski.jpg"
    },
    {
      "title": "Aishamanda Maretya Widyadhana",
      "category": "Project Collaborators",
      "affiliation": "Universitas Indonesia",
      "image": "/assets/images/people/tya.jpg"
    },
    {
      "title": "Azellia Anggun Viedyarani",
      "category": "Project Collaborators",
      "affiliation": "Universitas Brawijaya",
      "image": "/assets/images/people/azel.jpg"
    },
    {
      "title": "Dimas Saputra",
      "category": "Project Collaborators",
      "affiliation": "Universitas Pendidikan Indonesia",
      "image": "/assets/images/people/dimas.jpg"
    },
    {
      "title": "Yasmin Ananda Putri",
      "category": "Project Collaborators",
      "affiliation": "Universitas Airlangga",
      "image": "/assets/images/people/yasmin.jpg"
    },
    {
      "title": "Prof. J. Stephen Downie",
      "category": "Academic Co-authors",
      "affiliation": "University of Illinois Urbana-Champaign",
      "image": "/assets/images/people/downie.jpg"
    },
    {
      "title": "Barbara S. Lancho Barrantes",
      "category": "Academic Co-authors",
      "affiliation": "University of Brighton",
      "image": "/assets/images/people/barbara.jpg"
    },
    {
      "title": "Savira Arumdini",
      "category": "Academic Co-authors",
      "affiliation": "BRIN",
      "image": "/assets/images/people/vira.jpg"
    },
    {
      "title": "Ria Ariani",
      "category": "Academic Co-authors",
      "affiliation": "BRIN",
      "image": "/assets/images/people/ria.jpg"
    },
    {
      "title": "Noorika Retno Widuri",
      "category": "Academic Co-authors",
      "affiliation": "BRIN",
      "image": "/assets/images/people/empty.jpg"
    },
    {
      "title": "Dedi Suprianto",
      "category": "Academic Co-authors",
      "affiliation": "Dispusip Kab. Sidrap",
      "image": "/assets/images/people/empty.jpg"
    }
  ] 
%}

<div class="projects">
{% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category text-capitalize">{{ category }}</h2>
  </a>
  {% assign filtered = projects | where: "category", category %}
  <div class="row row-cols-1 row-cols-md-5 g-4">
    {% for person in filtered %}
    <div class="col">
      <div class="card h-100">
        <img src="{{ person.image }}" class="card-img-top" alt="{{ person.title }}" style="object-fit: cover; height: 100px;">
        <div class="card-body text-center">
          <h5 class="card-title">{{ person.title }}</h5>
          <p class="card-text text-muted">{{ person.affiliation }}</p>
        </div>
      </div>
    </div>
    {% endfor %}
  </div>
{% endfor %}
</div>