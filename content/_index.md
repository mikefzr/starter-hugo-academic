---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
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
        - title: Bachelor of Economics
          company: South China Agricultural University
          company_url: 'https://english.scau.edu.cn/'
          company_logo: org-gc
          location: Guangzhou
          date_start: '2018-06-01'
          date_end: '2022-06-01'
          description: |2-
              Finance
        - title: Master of Commerce
          company: University of New South Wales
          company_url: 'https://www.unsw.edu.au/'
          company_logo: org-x
          location: Sydney
          date_start: '2023-05-29'
          date_end: 
          description: Finance
    design:
      columns: '2'
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        The only way to have a friend is to be one.
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
