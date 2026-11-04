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
      username: me_ja
      text: ''
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: '私について'
        education: '学歴'
        interests: '興味のある分野のキーワード'
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
      title: '私の研究'
      subtitle: ''
      text: |-
        <div style="width: 85vw; max-width: 1300px; position: relative; left: 50%; transform: translateX(-50%);">

        日笠山諒亮は、拓殖大学コンピュータグラフィックス研究室の修士課程に在籍している。彼の研究は、表現力豊かなモーション合成に焦点を当てており、キャラクターの動きにおける力感や誇張表現を強化するためのデータ駆動型手法を探求している。また、モーション解析の補助情報として筋電図（EMG）を活用する研究にも取り組んでいる。
        </div>
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 主なプロジェクト
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
      title: 学会発表・ポスター
      text: |-
        <div style="width: 85vw; max-width: 1300px; position: relative; left: 50%; transform: translateX(-50%);">
        <div style="text-align: center;">
          <h3>国際会議</h3>
        </div>
      

        * **[口頭発表]** 「Comparing Rodrigues Vectors  and 6D Rotation Representations for Laplacian Motion Stitching」 <br>- [SIGGRAPH ASIA 2026](https://asia.siggraph.org/2026/) (2026年12月)
        * **[口頭発表]** 「Smooth Motion Stitching via Laplacian Optimization in Rodrigues Vector Space」 <br>- [NICOGRAPH International 2026](https://www.art-science.org/nicograph/nicoint2026/) (2026年6月)
        * **[ポスター発表]** 「A Hybrid Workflow for Anime Facial Expression Synthesis via Part Editing and Image-to-Image Redrawing」 <br>- [IEVC 2026](https://www.iieej.org/en/ievc/ievc2026/) (2026年3月)
        <div style="text-align: center;">
          <h3>国内会議</h3>
        </div>

        * **[ポスター発表]** 「ラプラシアンモーション接続における回転表現の比較」 <br>- [Visual Computing 2026](https://visualcomputing.jp/vc2026/) (2026年10月)
        * **[口頭発表]** 「ロドリゲスベクトルの回転不連続特性分析とモーション編集への影響評価」 <br>- [情報処理学会 第88回全国大会](https://www.ipsj.or.jp/event/taikai/88/index.html) (2026年3月)
        * **[口頭発表]** 「異なる力感をもつ動作を切り貼り可能にするラプラシアンベースのモーション誇張手法」 <br>- [NICOGRAPH 2025](https://www.art-science.org/nicograph/nico2025/) (2025年12月)
        </div>
    design:
      columns: '1'
  
  - block: collection
    id: news
    content:
      title: 最新のお知らせ
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
