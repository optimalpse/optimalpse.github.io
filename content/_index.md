---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        About us
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The group has two main branches of research, on one hand, developing new and more efficient optimisation, reinforcement learning and machine learning algorithms that allow to solve general problems in the systems domain. On the other hand, applying existing state-of-the-art techniques to address current challenges in process engineering. Our main area of application has been bioprocesses, although we work on other areas, such as fluid dynamics, photonic mirrors, superstructure optimisation, amongst a few others. 
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the group members →" %}}
    design:
      columns: '1'
---