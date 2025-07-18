---
# Leave the homepage title empty to use the site title
title: Stathis Galanakis
date: 2023-05-29
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        - title: Research Assistant in Computer Visio
          company: Imperial College London
          company_url: ''
          company_logo: ''
          location: London
          date_start: '2025-03-01'
          date_end: 
          description: In my role as a research assistant, my research interests lie on investigating diffusion-based approaches for reliable skin-lesion synthesis, classification and segmentation.

        - title: Computer Vision Intership
          company: Huawei UK 
          company_url: ''
          company_logo: ''
          location: London
          date_start: '2024-09-01'
          date_end: '2025-03-01'
          description: 'I worked as a Computer Vision Intern in Huawei UK, where I focus on 3D facial reconstruction from monocular images using advanced 3D Gaussian Splatting techniques.'            
        - title: Computer Vision Intership
          company: Huawei UK 
          company_url: ''
          company_logo: ''
          location: London
          date_start: '2022-01-25'
          date_end: '2024-01-25'
          description: 'As a Computer Vision Engineer at Huawei UK, I specialized in 3D facial reconstruction from monocular images. In this role, I integrated cutting-edge techniques to advance the field, focusing on enhancing the accuracy and effectiveness of reconstruction methods. My work involved pushing the boundaries of state-of-the-art approaches, such as NeRF and diffusion-based techniques.'
        - title: Research Assistant
          company: Imperial College London 
          company_url: ''
          company_logo: ''
          location: London
          date_start: '2021-02-01'
          date_end: '2022-01-22'
          description: 'I worked as a Research Assistan(RA) in the project ARISE held by Business School, Imperial College of London. ARISE was a European Union-funded initiative designed to forecast agricultural crop yields within a specific region during targeted time periods. My responsibilities encompassed the utilization of data derived from satellites and weather stations, employing state-of-the-art machine learning algorithms to extract meaningful insights. Additionally, I was tasked with generating synthetic data for regions with limited data availability, ensuring a comprehensive and robust approach to yield prediction.'
        - title: Computer Vision Scientist
          company: ArielAI
          company_url: ''
          company_logo: ''
          location: London
          date_start: '2020-01-01'
          date_end: '2020-10-01'
          description: 'My main responsibilities included the design and implementation of cutting-edge automated pipelines for collecting images across the web. These pipelines were instrumental in the creation of novel datasets that accurately represented real-world scenarios. In addition, I took charge of designing and coordinating human annotation tasks for the annotators at ArielAI while ensuring precise and consistent annotations..'
        - title: R&D, ML Engineer
          company: Pobuca Ltd
          company_url: ''
          company_logo: ''
          location: Athens
          date_start: '2018-05-01'
          date_end: '2019-01-31'
          description: "In my capacity as the sole Machine Learning Engineer, I undertook the development of a robust network for automated product recognition within images captured from supermarket shelves. This required designing Computer Vision algorithms and tools for easy annotation 
          and creating both training and detection procedures alongside with back-end support."
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
 # - block: contact
 #   id: contact
 #   content:
 #     title: Contact
 #     subtitle:
 #     text: |-
 #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
 #     # Contact (add or remove contact options as necessary)
 #     email: test@example.org
 #     phone: 888 888 88 88
 #     appointment_url: 'https://calendly.com'
 #     address:
 #       street: 450 Serra Mall
 #       city: Stanford
 #       region: CA
 #       postcode: '94305'
 #       country: United States
 #       country_code: US
 #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
 #     office_hours:
 #       - 'Monday 10:00 to 13:00'
 #       - 'Wednesday 09:00 to 10:00'
 #     contact_links:
 #       - icon: twitter
 #         icon_pack: fab
 #         name: DM Me
 #         link: 'https://twitter.com/Twitter'
 #       - icon: skype
 #         icon_pack: fab
 #         name: Skype Me
 #         link: 'skype:echo123?call'
 #       - icon: video
 #         icon_pack: fas
 #         name: Zoom Me
 #         link: 'https://zoom.com'
 #     # Automatically link email and phone or display as text?
 #     autolink: true
 #     # Email form provider
 #     form:
 #       provider: netlify
 #       formspree:
 #         id:
 #       netlify:
 #         # Enable CAPTCHA challenge to reduce spam?
 #         captcha: false
 #   design:
 #     columns: '2'
---
