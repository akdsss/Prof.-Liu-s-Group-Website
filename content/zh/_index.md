---
# Leave the homepage title empty to use the site title
title:
date: 2025-07-04
type: landing

sections:
  - block: hero
    content:
      title: |
        刘鸿课题组
      image:
        filename: LhGroup.jpg
      text: |
        <br>
        
        欢迎访问刘鸿课题组！
  
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
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: 近期论文发表
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
