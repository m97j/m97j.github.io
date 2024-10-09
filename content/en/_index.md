---
title:
date: 2024-09-24
type: landing



sections:
  - block: features
    content:
      title: <span style="font-size:70%">Minjae Kim's HomePage </span>
      text: <br><span style="font-size:125%">Welcome to my homepage, I am currently studying in the Department of Computer Science at Jeonbuk National University.</span> <br><br>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Interest in</span>
        content: <span style="font-size:70%">My areas of interest</span>
        align: center
        background:
          image:
            filename: interest.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Game Programming</span>
        content: <span style="font-size:70%">Develop Game using by Game Engine such as Unity or Unreal Engine<span style="font-size:70%">
        align: center
        background:
          image:
            filename: game_dev.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Virtual Reality</span>
        content: <span style="font-size:70%">Develop VR contents that improve users experiences</span>
        align: center
        background:
          image:
            filename: vr.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">That improves interaction between user and computer</span>
        align: center
        background:
          image:
            filename: ai.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Quantum Computing</span>
        content: <span style="font-size:70%">Studying quantum computing technology to enable complex calculations and develop higher quality programs.</span>
        align: center
        background:
          image:
            filename: qc.png
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
      interval: 2500
  
  - block: features
    id: interested_in
    content:
      title: Interested Areas
      text: 
      items:
       - name: Game Development
         icon: fas fa-gamepad
         description: I am interested in developing 3D games using game engines like Unity and Unreal, and languages such as C#.
       - name: VR Content Development
         icon: fas fa-vr-cardboard
         description: I am interested in VR content that allows 3D game users to experience a greater sense of realism.
       - name: Artificial Intelligence Technologies
         icon: fas fa-robot
         description: Applying technologies like natural language processing and deep learning in games to make interactions between users and characters more natural.
       - name: Graphics Technologies
         icon: fas fa-palette
         description: Studying Unreal5's Nanite technology to enable real-time rendering even when creating models with high polygons.
       - name: Quantum Computing Technology
         icon: fas fa-atom
         description: Studying quantum computing technology with better performance to run high-quality and heavy game programs smoothly.
       - name: Cloud Computing
         icon: fas fa-cloud
         description: Interested in cloud computing and network technologies to lower entry barriers such as required specifications for playing games.

  

  - block: collection
    content:
      id: section-1
      title: Blogs
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - blog
    design:
      view: community/customcard
      columns: '2'

  - block: collection
    content:
      id: section-2
      title: Projects
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - projects
    design:
      view: community/custom_cpt
      columns: '2'


  - block: collection
    content:
      id: section-3
      title: Study Notes
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - study
    design:
      view: community/custom_wall
      columns: '2'

---
