---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Лаборатория нелинейной оптики наноструктур и фотонных кристаллов
      image:
        filename: Logo2.gif
      text: |
        Основные направления деятельности в лаборатории -- исследования нелинейных и магнитных эффектов в микроструктурах, исследования эффектов в метаматериалах и фотонных кристаллах, а также изготовление микроструктур методом двухфотонной лазерной литографии.

  - block: collection
    content:
      title: <h2>Последние новости</h2>
      subtitle: "[Все новости >>](/ru/post)"
      text:
      count: 5
      filters:
        author: ""
        category: ""
        exclude_featured: false
        publication_type: ""
        tag: ""
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact #card
      columns: "2"

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ""
  #     text:
  #   design:
  #     columns: "1"
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
  #       padding: ["20px", "0", "20px", "0"]
  #     css_class: fullscreen

  - block: collection
    content:
      title: <h2>Последние публикации</h2>
      subtitle: "[Все публикации >>](/ru/publication)"
      text:
      count: 3
      filters:
        folders:
          - publication
        publication_type: "article-journal"
      sort_by: "Date"
    design:
      view: list #compact # publications  #  #citation
      columns: "2"

  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: "1"
---
