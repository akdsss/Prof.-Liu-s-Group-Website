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
            Computation, Simulation and Experiment of (Bio)macromolecules Lab
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

  # - block: hero
  #   content:
  #     title: |
  #       Computation, Simulation and Experiment of (Bio)macromolecules Lab
  #     image:
  #       filename: LhGroup.jpg
  #     text: |
  #       <br>
        
  #       Welcome to Computation, Simulation and Experiment of (Bio)macromolecules Lab!
 
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'
 
  - block: collection
    content:
      title: Latest News
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

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
