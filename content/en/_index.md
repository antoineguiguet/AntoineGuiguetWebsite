---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Antoine Guiguet, PhD
      image:
        filename: welcome.jpg
      text: |
        <br>

        Researcher and curator for Hymenoptera at the Muséum national d'Histoire naturelle in Paris. My research explores the evolution and molecular ecology of plant-insect interactions, with a focus on the mechanisms and adaptive significance of gall induction by insects.

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: news
    design:
      view: card
      columns: '3'

  - block: collection
    content:
      title: Recent Publications
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: citation
      columns: '2'
---