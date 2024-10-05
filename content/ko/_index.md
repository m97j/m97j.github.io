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
      text: 저에 대해 더 자세히 알아보세요!
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
