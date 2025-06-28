---
# Page title
title: Тематика
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts
  - block: collection
    id: section-1
    content:
      title: Тематика
      # subtitle: "Вот таким мы тут занимаемся"
      text: 

      # Display content from the `content/post/` folder
      filters:
        folders:
          - our-research
      sort_ascending: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view:  list #publications #publications # #card #list #compact  # showcase  masonry
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: false
    
  - block: markdown
    id: eq
    content:
      title: Оборудование 
      # subtitle: Всё, что необходимо для нобелевки
      text: "- Двухфотонный литограф\n
      - Конфокальный микроскоп и спектрометр\n
      - Спектрометр\n
      - 
      "

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
---