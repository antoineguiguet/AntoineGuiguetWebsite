---
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Antoine Guiguet
      image:
        filename: welcome.jpg
      text: |
        <br>

        <div class="hero-subtitle">Researcher &amp; Curator for Hymenoptera · Muséum national d'Histoire naturelle</div>

        Exploring the evolution and molecular ecology of plant-insect interactions, with a focus on the mechanisms and adaptive significance of gall induction by insects.

        {{% cta cta_link="../research/" cta_text="Read my research →" %}}
        {{% cta cta_link="../collection/" cta_text="Hymenoptera Collection →" %}}
    design:
      spacing:
        padding: ['20px', '0', '10px', '0']

  - block: collection
    content:
      title: Latest News
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
      page_type: news
    design:
      view: compact
      columns: '1'
      spacing:
        padding: ['10px', '0', '10px', '0']

  - block: collection
    content:
      title: Recent Publications
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
      page_type: publication
    design:
      view: citation
      columns: '1'
      spacing:
        padding: ['10px', '0', '20px', '0']
---