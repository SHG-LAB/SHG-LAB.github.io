---
# Page title
title: Research
# Page type - we want a landing page (such as a homepage)
type: landing

share: false

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts
  - block: collection
    id: section-1
    content:
      title: Research Areas of Our Laboratory
      subtitle: ㅤ
      text: "Projects fall loosely into the following broad directions: <br> <br>"

      # Display content from the `content/post/` folder
      filters:
        folders:
          - research #our-research
      sort_ascending: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view:  list #publications #publications # #card #list #compact  # showcase  masonry
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: false
    
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