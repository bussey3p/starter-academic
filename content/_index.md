---
# Leave the homepage title empty to use the site title
title: Trey Bussey
date: 2023-12-01
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
    id: skills
    content:
      title: Skills
      items:
        - name: Data Analysis
          description: 
          icon: r-project
          icon_pack: fab
        - name: Crime Mapping
          description: 
          icon: map
          icon_pack: fa
        - name: Course Development
          description: 
          icon: chalkboard
          icon_pack: fa
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
        - title: PhD Student | Criminal Justice
          company: University of Cincinnati
          company_url: ''
          company_logo: cin
          location: Cincinnati, OH
          date_start: '2024-08-01'
          date_end: '2027-05-01'
          description:
        - title: PhD Student | Criminology and Criminal Justice
          company: University of Nebraska Omaha
          company_url: ''
          company_logo: uno
          location: Omaha, NE
          date_start: '2022-08-01'
          date_end: '2024-05-01'
          description:
        - title: MS | Criminal Justice
          company: Radford University
          company_url: ''
          company_logo: radford
          location: Radford, VA
          date_start: '2020-08-01'
          date_end: '2022-05-01'
          description: 
        - title: BS | Criminal Justice
          company: Radford University
          company_url: ''
          company_logo: radford
          location: Radford, VA
          date_start: '2017-08-01'
          date_end: '2020-05-01'
          description: 
    design:
      columns: '2'
  - block: accomplishments
    id: certifications
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certifications'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.radford.edu/content/grad/home/academics/certificates/crime-analysis.html
          date_end: ''
          date_start: '2022-05-01'
          description: ''
          icon: chart-simple
          icon_pack: fa
          organization: Radford University
          organization_url: 
          company_logo: radford
          title: Crime Analysis Certificate
          url: ''
        - certificate_url: https://www.unomaha.edu/innovative-and-learning-centric-initiatives/services-we-offer/digital-learning/faculty-professional-development/foundations-of-teaching-online.php
          date_end: ''
          date_start: '2024-06-01'
          description: ''
          icon: chalkboard
          icon_pack: fa
          organization: University of Nebraska Omaha
          organization_url: 
          company_logo: uno
          title: Foundations of Teaching Online
          url: ''  
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
          - project2
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false      
 # - block: collection
   # id: featured
    #content:
      #title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: busseypt@mail.uc.edu
      address:
        street: 2610 University Circle
        city: Cincinnati
        region: OH
        postcode: '45221'
        country: United States
        country_code: US
      directions: CECH Criminal Justice
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
