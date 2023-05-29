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
    id: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
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
  - block: experience
    id: experience
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
        - title: Research Assistant
          company: The Hang Seng University of Hong Kong
          company_url: 'https://www.hsu.edu.hk/en/'
          company_logo: hsu
          location: Hong Kong, China
          date_start: '2022-01-01'
          date_end: '2022-05-31'
        - title: Java Software Engineer Intern
          company: Alibaba Group
          company_url: 'https://www.alibabagroup.com/'
          company_logo: alibaba
          location: Beijing, China
          date_start: '2021-06-01'
          date_end: '2021-08-30'
        - title: General Software Engineer Intern
          company: Huawei
          company_url: 'https://www.huawei.com/en/'
          company_logo: huawei
          location: Hangzhou, China
          date_start: '2021-08-01'
          date_end: '2020-11-03'
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
#       [Filter Publications](./publication/)
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
        If you have any question, please drop me a message here or send email to me.
      # Contact (add or remove contact options as necessary)
      email: sfofgalaxy@gmail.com
      phone: 086 173 4201 7609
      address:
        street: 8 Tao Ching Rd.
        city: Singapore
        region: Singapore
        postcode: '618724'
        country: Singapore
        country_code: SG
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
