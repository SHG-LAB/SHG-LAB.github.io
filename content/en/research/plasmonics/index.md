---
# Page title
title: Nanoplasmonics 
date: 2001-01-01
# Page type - we want a landing page (such as a homepage)
type: landing
show_date: false
share: false
# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts

    
  - block: markdown
    content:
      title:  <h3>Research directions</h3> #<h3>[Направления исследований](/ru/research) </h3>
      subtitle:  1 Nanoplasmonics <br>  2 [Nonlinear Optical Microscopy](/en/research/nlmicroscopy) <br> 3 [Two-Photon Laser Lithography](/en/research/lithography) <br> 4 [Magneto-Optics](/en/research/magnetooptics)
      text: "# Nanoplasmonics  
            
            
          ....
          "
#  цель -- http://localhost:1313/ru/research/
#  http://localhost:1313/content/ru/research/                                
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      gradient_start: '#4bb4e3'
      gradient_end: '#2b94c3'
    # The gradient angle from 0-360 degrees
      gradient_angle: 180
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
      text_color_light: true
  - block: collection
    content:
      title: Publications on this topic
      text: ""
      count: 999
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
        tag: Plasmonics
    design:
      view: list
      columns: '2'
---
<!-- Описание навправления для карточки -- вроде бы не видно в полном тексте  -->

<!-- 1 Наноплазмоника <br>  2 [Метаматериалы и фотонные кристаллы](/ru/research/metamaterials) <br> 3 [Нелинейная микроскопия](/ru/research/nlmicroscopy) <br> 4 [Двухфотонная лазерная литография](/ru/research/lithography) <br> 5 [Магнитооптика](/ru/research/magnetooptics) -->

