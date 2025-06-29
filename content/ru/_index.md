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
      subtitle: # "[Все новости >>](/ru/post)"
      text:
      count: 3
      filters:
        folders: 
          - post
        author: ""
        category: ""
        exclude_featured: false
        publication_type: 
        tag: ""
      sort_by: "Date"
      offset: 
      # order: desc
      page_type: 
    design:
      view: compact #card showcase
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
      subtitle: # "[Все публикации >>](/ru/publication)"
      text:
      count: 3
      filters:
        folders:
          - publication
        #publication_type: 
      sort_by: "Date"
      page_type: 
    design:
      view: list #compact # publications  #  #citation
      columns: "2"


  - block: contact
    id: contact_us
    content:
      title: "Связаться с нами:"
      text: |-
      email: test@example.org
      phone: +7 495 939-36-69
      address:
        street: Ленинские горы, д. 1, стр. 62
        city: Москва
        region: 
        postcode: ' '
        country: 
        country_code: 
      coordinates:
        latitude: '55.706665'
        longitude: '37.520557'
      directions: Корпус нелинейной оптики, комната 408
      # office_hours:
      #   - 'ПН-ПТ с 11:00 до 19:00'
        
      #appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '1'
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: "1"
  
---
