---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: People
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Research Staff
          - PhD students
          - Students
          - Grad Students
          # - Administration
          - Visitors
          - Alumni
      sort_by: Params.weight
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: Logo2.gif
          filters:
            brightness: 1
          parallax: true
          position: center
          size: actual # contain #cover
          text_color_light: true
      spacing:
        padding: ['30px', '0', '30px', '0']
      css_class: fullscreen
---