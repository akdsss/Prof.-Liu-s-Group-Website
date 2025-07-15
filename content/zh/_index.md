---
title:
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle:
      text: |
          <div class="main-head">
            CSEM Lab
          </div>
          <hr style=" width: 100%; height: 2px; background: white;">
          <div class="main-text">
            （生物）高分子计算模拟实验室
          </div>

    design:
      columns: '1'
      background:
        image: 
          filename: main_background.jpg
          filters:
            brightness: 0.8
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: collection
    content:
      title: 近期新闻
      subtitle:
      text:
      count: 5
      filters:
        folders:
          - news
        # author: ''
        # category: ''
        # exclude_featured: false
        # publication_type: ''
        # tag: ''
      # offset: 0
      # order: desc
      # page_type: post
    design:
      view: compact
      columns: '1'
---
