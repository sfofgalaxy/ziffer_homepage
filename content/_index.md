---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
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
        - title: Data Engineer
          company: Shopee
          company_url: 'www.shopee.com'
          company_logo: shopee
          location: Singapore
          date_start: '2022-06-26'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Real-time data
              * Flink launcher
        - title: MSc in Information Technology
          company: The Hong Kong University of Science and Technology
          company_url: 'https://hkust.edu.hk/'
          company_logo: hkust
          location: Hong Kong, China
          date_start: '2021-09-01'
          date_end: '2022-06-15'
        - title: BEng in Software Engineer
          company: Zhejiang University
          company_url: 'https://www.zju.edu.cn/english/'
          company_logo: zju
          location: Hangzhou, China
          date_start: '2017-09-01'
          date_end: '2021-06-30'
    design:
      columns: '2'
  - block: collection
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: sfofgalaxy@gmail.com
      phone: 086 173 4201 7609
      address:
        street: 5200 North Lake Rd.
        city: Merced
        region: CA
        postcode: '95343'
        country: United States
        country_code: US
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
