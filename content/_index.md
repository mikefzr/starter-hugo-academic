---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Undergraduate
          company: South China Agricultural University
          company_url: 'https://english.scau.edu.cn/'
          company_logo: org-gc
          location: Guangzhou, China
          # date_start: '2018-06-01'
          # date_end: '2022-06-01'
          description: |2-
              Finance:

              * Analysing
              * Modelling
              * Deploying
        - title: Postgraduate
          company: University of New South Wales
          company_url: 'https://www.unsw.edu.au/'
          company_logo: org-x
          location: Sydney, Australia
          # date_start: '2016-01-01'
          # date_end: '2020-12-31'
          description: Master of Commerce
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: z5443867@ad.unsw.edu.au
      phone: +61 0492845672
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/suzumiya233'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
