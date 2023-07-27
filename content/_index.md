---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 
      # icon: r-project
      # icon_pack: fab
      name: R
    - description: 
      # icon: chart-line
      # icon_pack: fas
      name: Phyton
    - description: 
      # icon: chart-line
      # icon_pack: fas
      name: Shiny
    - description: 
      # icon: camera-retro
      # icon_pack: fas
      name: Network Analysis
    - description: 
      # icon: camera-retro
      # icon_pack: fas
      name: Causal Inference
    - description: 
      # icon: camera-retro
      # icon_pack: fas
      name: Machine Learning
    - description: 
      # icon: camera-retro
      # icon_pack: fas
      name: GIS
    - description: 
      # icon: camera-retro
      # icon_pack: fas
      name: ETL
    - description: 
      # icon: camera-retro
      # icon_pack: fas
      name: Stata
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: The Brookings Institution
      company_logo: 
      company_url: https://www.brookings.edu/collection/workforce-of-the-future-initiative/
      date_end: ""
      date_start: "2021-01-01"
      description: |2-
          Worked on:

          * Data visualization and Shiny apps development
          * Machine Learning and Network Analysis for economic complexity and workforce development research
          * Development and testing of employment forecasts
          * Analysis of job tasks, skills, on-the-job training, and educational requirements
          
      location: Washington, DC
      title: Research Analyst (Contractor)
    - company: Nosis Lab
      company_logo: 
      company_url: https://www.nosis.com/es
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: |2-
          Worked on:

          * Development, monitoring and back-testing of credit risk models
          * Machine learning models to predict income within small geographic units
          * GIS, market segmentation, and customer life cycle dashboards
          * ETL and reporting automation
      
      location: Buenos Aires
      title: Credit Risk and Big Data Consultant
    title: Experience
  design:
    columns: "2"
# - block: accomplishments
#   content:
#     date_format: Jan 2006
#     items:
#     - certificate_url: https://www.coursera.org
#       date_end: ""
#       date_start: "2021-01-25"
#       description: ""
#       organization: Coursera
#       organization_url: https://www.coursera.org
#       title: Neural Networks and Deep Learning
#       url: ""
#     - certificate_url: https://www.edx.org
#       date_end: ""
#       date_start: "2021-01-01"
#       description: Formulated informed blockchain models, hypotheses, and use cases.
#       organization: edX
#       organization_url: https://www.edx.org
#       title: Blockchain Fundamentals
#       url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#     - certificate_url: https://www.datacamp.com
#       date_end: "2020-12-21"
#       date_start: "2020-07-01"
#       description: ""
#       organization: DataCamp
#       organization_url: https://www.datacamp.com
#       title: Object-Oriented Programming in R
#       url: ""
#     subtitle: null
#     title: Accomplish&shy;ments
#   design:
#     columns: "2"
# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - post
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Recent Posts
#   design:
#     columns: "2"
#     view: compact
#   id: posts
- block: portfolio
  content:
    # buttons:
    # - name: All
    #   tag: '*'
    # - name: Deep Learning
    #   tag: Deep Learning
    # - name: Other
    #   tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    title: Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Media
  design:
    columns: "2"
    view: card
  id: featured
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
- block: contact
  content:
    # address:
    #   city: Stanford
    #   country: United States
    #   country_code: US
    #   postcode: "94305"
    #   region: CA
    #   street: 450 Serra Mall
    # appointment_url: https://calendly.com
    # autolink: true
    contact_links:
    # - icon: twitter
    #   icon_pack: fab
    #   link: https://twitter.com/Twitter
    #   name: DM Me
    # - icon: skype
    #   icon_pack: fab
    #   link: skype:echo123?call
    #   name: Skype Me
    # - icon: video
    #   icon_pack: fas
    #   link: https://zoom.com
    #   name: Zoom Me
    # directions: Ciudad Autónoma de Buenos Aires, Argentina 
    email: cdaboin2@gmail.com
    # form:
    #   formspree:
    #     id: null
    #   netlify:
    #     captcha: false
    #   provider: netlify
    # office_hours:
    # - Monday 10:00 to 13:00
    # - Wednesday 09:00 to 10:00
    # phone: 888 888 88 88
    # subtitle: null
    # text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
    #   ut magna et, vehicula efficitur enim.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
