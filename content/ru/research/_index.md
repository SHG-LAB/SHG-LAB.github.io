---
# Page title
title: Научные направления лаборатории
# Page type - we want a landing page (such as a homepage)
type: landing

share: false

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts
  - block: collection
    id: section-1
    content:
      title: Научные направления лаборатории
      subtitle: ㅤ
      text: "Исследования нашей лаборатории могут быть условно разделены на следующие направления: <br>  <br>" 

      # Display content from the `content/post/` folder
      filters:
        folders:
          - research
      sort_ascending: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view:  list #publications #publications # #card #list #compact  # showcase  masonry
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: false


  - block: markdown
    content:
      title:
      subtitle: ""
      text: ‎
          ![](team1.jpg)
    # design:
    #   columns: "1"
    #   background:
    #     image:
    #       filename: team1.jpg
    #       filters:
    #         brightness: 1
    #       parallax: false
    #       position: center
    #       size: cover
    #       text_color_light: true
    #   spacing:
    #     padding: ["20px", "0", "20px", "0"]
    #   css_class: fullscreen  
  # - block: markdown
  #   id: eq
  #   content:
  #     title: Оборудование 
  #     # subtitle: Всё, что необходимо для нобелевки
  #     text: "- Двухфотонный литограф\n
  #     - Конфокальный микроскоп и спектрометр\n
  #     - Спектрометр\n
  #     - 
  #     "

  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '2'
---