---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: Open Heat Lab
          content: Our lab explores at the intersections of thermal science, nanotechnology, and ultrafast physics, with a focus on probing mechanisms and pushing limits.
          align: left
          align_content: "align-items-end"
          text_shadow: "2px 2px 8px #000"
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: team.jpeg
              filters:
                brightness: 1
              size: contain
            position: left
            color: '#fff'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 5000


  
  
  
  - block: collection
    content:
      title: Recent and Upcoming Events
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event
    design:
      view: card
      columns: '1'
    
---
