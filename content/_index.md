---
# Leave the homepage title empty to use the site title
title: Home
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Research
      image:
        filename: welcome.jpg
      text: |
        <br>
  
  - block: collection
    content:
      title: Publications
      subtitle:
      text:
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: collection
    content:
      title: Assessments
      text: ""
      count: 
      filters:
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: People
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
