---
title: 'Home'
date: 2024-09-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: 김민재의 홈페이지에 오신 것을 환영합니다.
      text: 🧱 저에 대해 더 자세히 알아보세요!  🧱
      primary_action:
        text: Go to github
        url: https://github.com/m97j
        icon: rocket-launch
      secondary_action:
        text: Read the blogs
        url: /blog/
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Interest in</span>
        content: <span style="font-size:70%">Interest in things</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: 

      - title: <span style="font-size:70%">Game Programming</span>
        content: <span style="font-size:70%">Unity, Unreal등의 게임 엔진을 이용하여 게임 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Virtual Reality</span>
        content: <span style="font-size:70%">사용자의 ~~이 증가하는 VR컨텐츠 개발</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">사용자와 컴퓨터 시스템의 상호작용을 더 실감나게 하는 기술</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Quantum Computing</span>
        content: <span style="font-size:70%">복잡한 계산을 가능하게 해 더 좋은 퀄리티의 프로그램 개발을 가능하게 하는 양자 컴퓨팅 기술 공부</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
  
  - block: features
    id: features
    content:
      title: Features
      text: Build your site with blocks 🧱
      items:
        - name: Optimized SEO
          icon: magnifying-glass
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Fast
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Easy
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: No-Code
          icon: code-bracket
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Highly Rated
          icon: star
          description: Rated 5-stars by the community.
        - name: Swappable Blocks
          icon: rectangle-group
          description: Build your pages with blocks - no coding required!
  

---
