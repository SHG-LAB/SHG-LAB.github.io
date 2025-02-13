---
# Page title
title: Магнитооптика 
date: 2005-01-01
# Page type - we want a landing page (such as a homepage)
type: landing
show_date: false

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts

    
  - block: markdown
    content:
      title: ؜  <h3> [Направления исследований](/ru/research) </h3>
      subtitle:  1 [Наноплазмоника](/ru/our-research/plasmonics) <br> 2 [Метаматериалы и фотонные кристаллы](/ru/our-research/metamaterials) <br> 3 [Нелинейная микроскопия](/ru/our-research/nlmicroscopy) <br> 4 [Двухфотонная лазерная литография](/ru/our-research/litography) <br> 5 Магнитооптика <br> <h3> [Оборудование](/ru/research/#eq)</h3>
      text: "<h1> Заголовок5 </h1> \n  
          Полное описание навправления \n
          - тык \n
          - мык \n"
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
      title: Публикации по этой теме
      text: ""
      count: 25
      filters:
        folders:
          - publication
        #publication_type: 'article'
        tag: 'Source Themes'  
    design:
      view: citation
      columns: '2'
---
Описание навправления для карточки -- вроде бы не видно в полном тексте 



<!-- ---
title: Двухфотонная лазерная литография
date: 2025-01-13

featured: true
show_date: false
reading_time: false
share: false
---
Парапампам -->

<!--more-->
<!-- Фьють! -->


<!-- ---
# Files in this folder represent a Widget Page (homepage)
type: widget_page
title: "Оптика метаматериалов и фотонных кристаллов"
authors: ["admin"]
show_date: false
---
Краткое описание направления  -->

<!-- ---
# Page title
title: Оптика метаматериалов и фотонных кристаллов
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: section-1
    content:
      title: Описание раз
      subtitle: A subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
#   - block: markdown
#     id: section-2
#     content:
#       title: Section 2
#       subtitle: A subtitle
#       text: Add your Section 2 content here...
--- -->



<!-- 
Краткое описание направления

Подробности  -->
