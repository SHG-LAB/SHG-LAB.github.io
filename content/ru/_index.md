---
# Leave the homepage title empty to use the site title
title: Лаборатория нелинейной оптики наноструктур и фотонных кристаллов
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title:  Лаборатория нелинейной оптики наноструктур и фотонных кристаллов
      image:
        filename: transparent.svg #  lab_cover_test.jpg #
        filters:
            brightness: 0.1
            opacity: 100
      text: | 
        Мы исследуем линейные и нелинейные оптические и магнитооптические эффекты в микроструктурах, метаматериалах и фотонных кристаллах, а также изготавливаем микроструктуры методом двухфотонной лазерной литографии. 
        <p class="hero-links-text">  <a href="https://www.phys.msu.ru" target="_blank" style="color: #d1d3d7;">Физический факультет МГУ</a> <br>  <a href="https://quantum.phys.msu.ru/ru"  target="_blank" style="color: #d1d3d7;">Кафедра квантовой электроники</a> </p>
    design:
      # Choose an optional background color, gradient, image, or video
      background:
         image:
          ### Add your image background to `assets/media/`.
          filename:  gr3__.jpg #lab_cover_test.jpg
          filters:
            brightness: 0.8
          parallax: true
          
         text_color_light: true
      columns: "1"
        #  gradient_end: '#dadade'
        #  gradient_start: '#f3f3f7'

  - block: collection
    content:
      title: Последние новости
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
      view: card # publications #compact #card showcase
      columns: "2"
    archive:
        enable: true
        text: Все новости
        link: post/


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
      title: Публикации
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
      title: "Связаться с нами"
      subtitle: 
      text: 
      email: contact+q@shg.ru
      phone: +7 495 939-36-69
      address:
        street: Ленинские горы, д. 1, стр. 62
        city: Москва
        region: 
        postcode: '119234'
        country: 
        country_code: 
      coordinates:
        latitude: '55.706714'
        longitude: '37.520730'
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
