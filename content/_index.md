---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas

  - block: collection
    content:
      title: Featured Publications and Preprints
      subtitle: Full list of publications --> https://roger.castellsgraells.com/publication
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: compact

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
        - title: Postdoctoral Researcher
          company: University of California Los Angeles (UCLA)
          company_url: ''
          company_logo: logo_UCLA_blue
          location: California, US
          date_start: '2020-01-19'
          date_end: ''
          description: Computational design and characterization of novel protein assemblies as imaging scaffolds for structural biology (cryo-EM) and biomedical applications in the lab of Prof. Todd Yeates.
          # description: |2-
              # Responsibilities include:

              # * Analysing
              # * Modelling
              # * Deploying
        - title: Postdoctoral Researcher
          company: John Innes Centre (JIC)
          company_url: ''
          company_logo: logo_jic
          location: UK
          date_start: '2019-10-01'
          date_end: '2020-01-10'
          description: Study and production of virus-like particles for biotechnology applications like vaccines. Horizon 2020 Pharma Factory project in the lab of Prof. George Lomonossoff.

        - title: PhD Student - John Innes Foundation Fellowship
          company: John Innes Centre (JIC)
          company_url: ''
          company_logo: logo_jic
          location: UK
          date_start: '2015-10-01'
          date_end: '2019-09-30'
          description: -**PhD Project:** Study of virus maturation using transient expression systems and biophysical and structural methods, including cryo-EM, in the lab of Prof. George Lomonossoff (PhD project, John Innes Centre, June 2016 – September 2019). 
             <br /> -**Collaborations with:**  <br />• Prof. Jack Johnson (The Scripps Research Institute, USA) <br /> • Prof. Neil Ranson (The Astbury Centre for Structural Molecular Biology, UK)  <br />• Prof. Tatiana Domitrovic (Universidade Federal do Rio de Janeiro, Brazil). <br />
              -**Rotation Projects:** <br />• Study of the alteration of host vesicular trafficking by an effector from *Phytophthora infestans* and study of the deletion of a gene cluster in tomato with CRISPR/Cas9 in the lab of Prof. Sophien Kamoun (Rotation 3, The Sainsbury Laboratory, March – May 2016). <br />• Study of starch synthesis in wheat grains in the lab of Prof. Alison Smith (Rotation 2, John Innes Centre, January – March 2016).<br /> • Production of engineered mosaic virus-like particles from turnip crinkle virus (TCV) in plants in the lab of Prof. George Lomonossoff (Rotation 1, John Innes Centre, October – December 2015).

        - title: Research Intern
          company: Centre for Research in Agricultural Genomics (CRAG)
          company_url: ''
          company_logo: logo_crag
          location: Spain
          date_start: '2014-10-01'
          date_end: '2015-02-28'
          description: Study of the structure of plant genomes looking at elements like transposons with bioinformatic tools. Mentored by Dr. Cristina Vives, Dr. Pere Puigdomènech and Dr. Josep M. Casacuberta.  

        - title: Research Intern - Amgen Scholars Fellowship
          company: Ludwig-Maximilians Universität München (LMU)
          company_url: ''
          company_logo: logo_lmu
          location: Germany
          date_start: '2014-07-01'
          date_end: '2014-09-10'
          description: Study of chloroplast membrane proteins, OEP21 and Tic-22, with Dr. Bettina Bölter in the lab of Prof. Jürgen Soll.

        - title: Research Intern - BUSS Fellowship
          company: University of Zurich (UZH)
          company_url: ''
          company_logo: logo_UZH
          location: Switzerland
          date_start: '2013-07-01'
          date_end: '2013-08-31'
          description: Study of the durable disease resistance gene Lr34 from wheat with Dr. Simon Krattinger in the lab of Prof. Beat Keller.

    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
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
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card



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
        
      # Contact (add or remove contact options as necessary)
      email: rcastellsg@ucla.edu
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: '@rcastellsg'
          link: 'https://twitter.com/rcastellsg'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
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
      columns: '2'
---
