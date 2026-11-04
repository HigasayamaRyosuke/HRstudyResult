---
# Leave the homepage title empty to use the site title
title: 'Ryosuke Higasayama'
summary: ''
date: 2022-10-24
type: landing
authors: ["admin"]

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: 'About Me'
        education: 'Educational background'
        interests: 'Keywords for areas of interest'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        <div style="width: 85vw; max-width: 1300px; position: relative; left: 50%; transform: translateX(-50%);">

        Ryosuke Higasayama is a master's student in the Computer Graphics Laboratory at Takushoku University. His research focuses on expressive motion synthesis, exploring data-driven methods to enhance the sense of force and exaggeration in character movements. He also investigates the use of electromyography (EMG) as supplementary information for motion analysis.
        </div>
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Key Projects
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  
  - block: markdown
    id: talks
    content:
      title: Conference Presentations & Posters
      text: |-
        <div style="width: 85vw; max-width: 1300px; position: relative; left: 50%; transform: translateX(-50%);">

        <div style="text-align: center;">
          <h3>International conference</h3>
        </div>

        * **[Conference]** 「Comparing Rodrigues Vectors and 6D Rotation Representations for Laplacian Motion Stitching」 <br>- [SIGGRAPH ASIA 2026](https://asia.siggraph.org/2026/) (2026/12)
        * **[Conference]** 「Smooth Motion Stitching via Laplacian Optimization in Rodrigues Vector Space」 <br>- [NICOGRAPH International 2026](https://www.art-science.org/nicograph/nicoint2026/) (2026/6)
        * **[Posters]** 「A Hybrid Workflow for Anime Facial Expression Synthesis via Part Editing and Image-to-Image Redrawing」 <br>- [IEVC 2026](https://www.iieej.org/en/ievc/ievc2026/) (2026/3)

        <div style="text-align: center;">
          <h3>Domestic conference</h3>
        </div>

        * **[Posters]** 「Comparing Rodrigues Vectors and 6D Rotation Representations for Laplacian Motion Stitching」 <br>- [Visual Computing 2026](https://visualcomputing.jp/vc2026/) (2026/10)
        * **[Conference]** 「Analyzed rotational discontinuities in Rodrigues vectors and evaluated their impact on motion editing.」 <br>- [Information Processing Society of Japan](https://www.ipsj.or.jp/event/taikai/88/index.html) (2026/3)
        * **[Conference]** 「Laplacian-Based Motion Exaggeration for Stitching Motions with Different Dynamics」 <br>- [NICOGRAPH 2025](https://www.art-science.org/nicograph/nico2025/) (2025/12)
      
        </div>
    design:
      columns: '1'
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  
---
