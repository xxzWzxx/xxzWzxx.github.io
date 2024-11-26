---
# Leave the homepage title empty to use the site title
title: "Zixiao's Homepage"
date: 2024-11-07
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
      button:
        text: Download CV
        url: uploads/CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I want to apply machine learning methods to traditional operations management problems to help people make good decisions efficiently and transparently. Currently, I decompose this goal into two parts: 

        (i) identifying and utilizing key problem structures that lead to efficiency and explainability in algorithms, 

        (ii) developing algorithms that systematically translate advances in machine learning into data-driven decision-making methods.
  
        I am currently focusing on business operation. I am willing to explore healthcare operation and other topics in the future!

        My dream is to make the world a better place through my research. 🌏
    design:
      columns: '1'
#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      view: article-grid
#      columns: 2
  - block: collection
    content:
      title: Working Paper
      text: ""
      filters:
        folders:
          - ongoing
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
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
---
