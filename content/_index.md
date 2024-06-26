---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
#      button:
#        text: Download CV
#        url: uploads/resume.pdf
    design:
      css_class: light
      background:
        color: white
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
#        image:
#          # Add your image background to `assets/media/`.
#          filename: stacked-peaks.svg
#          filters:
#            brightness: 1.0
#          size: cover
#          position: center
#          parallax: false
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: community/article-grid
      fill_image: false
      columns: 3
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
#        featured_only: true
        exclude_featured: false
    design:
      view: community/article-grid
      fill_image: false
      columns: 3
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
#  - block: collection
#    content:
#      title: Recent Publications
#      text: ""
#      filters:
#        folders:
#          - publication
#        exclude_featured: false
#    design:
#      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: article-grid
#      columns: 1
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: date-title-summary
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
  - block: collection
    id: collaborations
    content:
      title: Experience & Collaborations
      filters:
        folders:
          - collaborations
    design:
      view: community/image-grid
      fill_image: false
      columns: 5
      show_date: false
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 10]
---
