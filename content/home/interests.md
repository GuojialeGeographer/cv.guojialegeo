---
# An instance of the Portfolio widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Research Interests
subtitle: 'Areas of Focus & Expertise'

content:
  # Page type to display. E.g. project.
  page_type: interests

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  filter_button:
    - name: All
      tag: '*'
    - name: GIS
      tag: GIS
    - name: Remote Sensing
      tag: RS
    - name: Machine Learning
      tag: ML
    - name: Spatial Analysis
      tag: SA

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false

# Research interests content
interests:
  - title: Geographic Information Systems
    description: |
      - Spatial data analysis and modeling
      - Web GIS development
      - Spatial database management
      - GIS application development
    image: gis.jpg
    tags:
      - GIS

  - title: Remote Sensing
    description: |
      - Satellite image processing
      - Land use/cover classification
      - Change detection
      - Environmental monitoring
    image: remote-sensing.jpg
    tags:
      - RS

  - title: Machine Learning in Geospatial Analysis
    description: |
      - Deep learning for image classification
      - Spatial pattern recognition
      - Predictive modeling
      - AI in GIS
    image: ml.jpg
    tags:
      - ML

  - title: Spatial Analysis
    description: |
      - Spatial statistics
      - Network analysis
      - Terrain analysis
      - Urban spatial structure
    image: spatial-analysis.jpg
    tags:
      - SA
---
