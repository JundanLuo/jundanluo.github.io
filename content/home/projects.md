---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: 'Projects'
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  # filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  # filter_button:
  #   - name: All
  #     tag: '*'
  #   - name: Machine Learning
  #     tag: ML
  #   - name: Computer Vision
  #     tag: CV
  #   - name: NLP
  #     tag: NLP
content:
    filters:
        folders:
            - projects
    featured_only: false
    exclude_featured: false
    exclude_future: false
    exclude_past: false

 # Choose how many pages you would like to display (0 = all pages)
count: 5
# Choose how many pages you would like to offset by
# Useful if you wish to show the first item in the Featured widget
offset: 0
# Field to sort by, such as Date or Title
sort_by: 'Date'
sort_ascending: false

design:
  columns: '1'
  view: compact
  flip_alt_rows: false
  background: {}
  spacing: {padding: [100, 0, 0, 0]}
---
