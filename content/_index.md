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
      button:
        text: Download CV
        url: uploads/CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: UW2.jpg
          filters:
            brightness: 0.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Honors and Awards'
      subtitle: ''
      text: |-
        <div style="font-size:16px; max-width:2000px;">
        
        - NESS Student Poster Award, *New England Statistical Society*, 2025. [[Link]](https://nestat.org/posterawards/nessposter2025/)

        - MMLS 2025 Honorable Mention Poster Award, *Midwest Machine Learning Symposium*, 2025. [[Link]](https://midwest-ml.org/2025/)

        - Frontiers in Statistical Machine Learning (FSML) Travel Award, *the Institute of Mathematical Statistics (IMS)*, 2025. [[Link]](https://fsmlims.wixsite.com/fsml25)

        </div>
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
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
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  - block: markdown
    id: talks
    content:
      title: 'Talks & Events'
      subtitle: ''
      text: |-
        <div style="font-size:16px;">
        
        #### Invited & Contributed Talk

        |                                                              |            |         |
        |--------------------------------------------------------------|------------|---------|
        | The 38th New England Statistics Symposium (NESS 2025)        | Yale       | 2025.06 |
        | Math Machine Learning seminar MPI MIS + UCLA                 | UCLA       | 2025.03 |
        | Institute for Foundations of Data Science Ideas Forum        | UW–Madison | 2024.11 |
        
        #### Poster Presentation

        |                                                              |              |         |
        |--------------------------------------------------------------|--------------|---------|
        | The Inaugural Workshop on Frontiers in Statistical Machine Learning (FSML) | Vanderbilt | 2025.08 |
        | Midwest Machine Learning Symposium (MMLS 2025)               | UChicago     | 2025.06 |
        | The 38th New England Statistics Symposium (NESS 2025)        | Yale         | 2025.06 |
        | Midwest Optimization & Statistical Learning Conference 2025  | Northwestern | [2025.05](https://www.mccormick.northwestern.edu/research/optimization-machine-learning-center/news-events/past-workshops.html) |
        | 6th Annual Data Science Research Bazaar                      | UW–Madison   | 2025.03 |
        | 100th Transportation Research Board (TRB) Annual Meeting     | Virtual      | 2021.01 |

        </div>
    design:
      view: list
      columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
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
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
