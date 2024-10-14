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
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: "#333333"
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: recent-news
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        I am passionate about developing advanced operation and planning tools for large-scale electric energy systems, enabling efficient, reliable, and secure decarbonization. My research agenda is centered around analyzing, designing, and improving principled and data-driven models and solution algorithms to address the pressing challenges of sustainable electric energy systems.

        My research draws on tools and theories from optimization, which allows us to articulate goals, tradeoffs, and restrictions, machine learning and artificial intelligence, which helps us leverage data to understand and act on systems, and large-scale optimization techniques, which establish the framework for solving massive optimization problems arising in modern networked systems. 
    design:
      columns: '1'
  - block: markdown
    content:
      title: 'Recent news'
      subtitle: ''
      text: |-
        <div style="font-size: 14px;">
          <ul>
          <li> <strong>Sep. 26, 2024:</strong> I will be presenting a poster  in "Learning to tune low-fidelity optimization models" at the launching event of the Center for Operations and Optimization in Process Systems (COOPS) at Purdue University.</li>
          <li> <strong>Jul. 24, 2024:</strong> I will be presenting at the panel "Outstanding Doctoral Dissertation in Power and Energy Systems" at IEEE PES General Meeting in Seattle.</li>
          <li> <strong>May 3, 2024:</strong> Happy to announce that I have been selected as a finalist for the 2024 IEEE PES PEEC Outstanding Doctoral Dissertation Award.</li>
          <li> <strong>Aug. 13, 2023:</strong> Accepted! Our paper G. E. Constante-Flores, Antonio J. Conejo, and Feng Qiu, "Daily Scheduling of Generating Units with Natural-Gas Market Constraints" has been accepted for publication in the European Journal of Operational Research. </li>
          <li> <strong>Jul. 17, 2023:</strong> I will be presenting our work in "Security-Constrained Unit Commitment: A Decomposition Approach Embodying Kron Reduction" at the International Conference in Stochastic Programming in Davis, CA.</li>
          <li> <strong>Jun. 8, 2023:</strong> Accepted! Our paper G. E. Constante-Flores and Antonio J. Conejo, "Security-Constrained Unit Commitment: A Decomposition Approach Embodying Kron Reduction" has been accepted for publication in the European Journal of Operational Research. </li>
          <li> <strong>Dec. 7, 2022:</strong>  I will be joining the group of Prof. Can li at Purdue University in January 2023 as a postdoctoral researcher.</li>					
          </ul>
    design:
      columns: '1'
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: news
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
  #     view: list
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
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
      columns: 1
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
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
