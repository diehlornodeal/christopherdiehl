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
  - block: features
    content:
      title: Skills
      items:
        - name: Reinforcement Learning
          #description: 90%
          icon: brain
          icon_pack: fas
        - name: Imitation Learning
          #description: EBM, CVAE, GAN, DDPM 
          icon: school
          icon_pack: fas
        - name: Generative Models
          icon: palette
          icon_pack: fas
        - name: Optimal Control
          #description: 10%
          icon: gear
          icon_pack: fas
        - name: Game Theory
          #description: 10%
          icon: chess
          icon_pack: fas
        - name: Differentiable Optimization
          #description: 10%
          icon: arrows-left-right
          icon_pack: fas
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
        - title: Research Scientist
          company: TU Dortmund University (Robotics Research Institute)
          company_url: ''
          #company_logo: org-gc
          location: Dortmund
          date_start: '2019-10-15'
          date_end: ''
          description: |2-
              Research projects together with industry partners (e.g., ZF AI Lab, Forvia) in large-scale motion prediction and model predictive control.
        - title: Perception Intern  
          company: Hella Aglaia Mobile Vision (aquired by Volkswagens CARIAD SE)
          company_url: ''
          #company_logo: org-x
          location: Berlin
          date_start: '2019-01-01'
          date_end: '2019-07-31'
          description: Developed novel multi-modal perception modules for multi-object detection, tracking and mapping.
        - title: Student Researcher  
          company: TU Dortmund University
          company_url: ''
          #company_logo: org-x
          location: Dortmund
          date_start: '2017-04-01'
          date_end: '2018-09-01'
          description: Developed novel motion prediction and planning using ML and optimization (project with ZF Group).
        - title: Simulation Intern  
          company: Bertrandt AG 
          company_url: ''
          #company_logo: org-x
          location: Cologne
          date_start: '2016-02-01'
          date_end: '2016-05-31'
          description: Implemented control strategies for a 5DOF driving simulator.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://ml4ad.github.io/2021/
          date_end: ''
          date_start: '2021-12-19'
          description: ''
          organization: Neural Information Processing Systems 2021 -  Workshop Machine Learning for Autonomous Driving
          #organization_url: https://www.coursera.org
          title: Best Paper Award 
          url: ''
        - #certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2022-12-01'
          #description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: Workshop Computational Intelligence
          #organization_url: https://www.edx.org
          title: Youth Author Award 
          #url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - #certificate_url: https://www.edx.org
          date_end: '2019-09-30'
          date_start: '2017-10-01'
          organization: WILO Foundation
          title: German Scholarschip
        # - certificate_url: https://www.datacamp.com
        #   date_end: '2020-12-21'
        #   date_start: '2020-07-01'
        #   description: ''
        #   organization: DataCamp
        #   organization_url: https://www.datacamp.com
        #   title: 'Object-Oriented Programming in R'
        #   url: ''
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
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
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to leave a message.
      # Contact (add or remove contact options as necessary)
      email: christopher.diehl@tu-dortmund.de
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: Otto-Hahn-Straße 8
        city: Dortmund
        region: NRW
        postcode: '44227 '
        country: Germany
        country_code: DE
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
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

