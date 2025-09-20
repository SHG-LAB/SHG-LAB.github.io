---
# Leave the homepage title empty to use the site title
title: Laboratory of nonlinear optics of nanostructures & photonic crystals
date: 
type: landing

sections:
  - block: hero
    content:
      title:  Laboratory of nonlinear optics of nanostructures & photonic crystals
      image:
        filename: transparent.svg #  lab_cover_test.jpg #
        filters:
            brightness: 0.9
            opacity: 100
      text: | 
        We study linear and nonlinear optical and magneto-optical effects in microstructures, metamaterials, and photonic crystals, and also fabricate microstructures using two-photon laser lithography.
        <p class="hero-links-text">  <a href="https://www.phys.msu.ru" target="_blank" style="color: #d1d3d7;">MSU, Faculty of Physics</a> <br>  <a href="https://quantum.phys.msu.ru/en"  target="_blank" style="color: #d1d3d7;">Department of Quantum Electronics</a> </p>
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

  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle: 
  #     text:
  #     count: 3
  #     filters:
  #       folders: 
  #         - post
  #       author: ""
  #       category: ""
  #       exclude_featured: false
  #       publication_type: 
  #       tag: ""
  #     sort_by: "Date"
  #     offset: 
  #     # order: desc
  #     page_type: 
  #   design:
  #     view: card # publications #compact #card showcase
  #     columns: "2"


  - block: collection
    content:
      title: Publications
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
      title: "Contacts"
      subtitle: 
      text: 
      email: contact+q@shg.ru
      phone: +7 495 939-36-69
      address:
        street: Leninskie Gory, 1с62
        city: Moscow
        region: 
        postcode: '119234'
        country: 
        country_code: 
      coordinates:
        latitude: '55.706714'
        longitude: '37.520730'
      directions: Nonlinear Optics Building, Room 408 
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
