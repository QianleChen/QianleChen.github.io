---
<!-- TODO: You can customize sections, titles, text content, and design settings here -->
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '🌍 My Research & Work'
      subtitle: ''
      text: |-
        I'm a Research Assistant at UCLA's Joint Institute for Regional Earth System Science and Engineering, where I analyze thermal satellite imagery to study wildfire progression and urban heat patterns. My work has been featured in NASA's Caltech Jet Propulsion Lab ECOSTRESS gallery.

        I'm passionate about applying data science and remote sensing to environmental challenges. Currently, I'm coordinating a $1M research project with the Orange County Fire Department to develop AI-based decision-support models for wildfire response and resource allocation.

        Through my nonprofit, Harmony with Nature, I bridge research and community action, promoting environmental stewardship through education and hands-on conservation initiatives. Let's collaborate to create a more sustainable future! 🌱
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: research
    content:
      title: Research
      subtitle: ''
      text: ''
      filters:
        folders:
          - Research
        exclude_featured: false
      count: 0
      order: desc
    design:
      view: card
      columns: 2
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: activities
    content:
      title: Activities
      subtitle: ''
      text: ''
      filters:
        folders:
          - Activities
        exclude_featured: false
      count: 0
      order: desc
    design:
      view: card
      columns: 2
---
