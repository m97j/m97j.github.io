---
title:
date: 2024-09-24
type: landing



sections:
  - block: features
    content:
      title: <span style="font-size:70%">Mj HomePage </span>
      text: <br><span style="font-size:125%">전북대학교 컴퓨터공학부에 재학중인 저의 홈페이지에 오신 것을 환영합니다.</span> <br><br>
        {{% cta cta_link="./about/" cta_text="find out →" %}}

  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Interest in</span>
        content: <span style="font-size:70%">관심있는 분야들</span>
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
            filename: game_dev.png
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
      interval: 2500
  
  - block: features
    id: interested_in
    content:
      title: 관심사들
      text: 관심있는 개발분야들과 관련 기술들
      items:
        - name: 게임개발
          icon: fas fa-gamepad
          description: Unity, Unreal등의 게임엔진과 C#등의 언어를 사용하여 3D게임을 개발하는 것에 관심이 있습니다.
        - name: VR컨텐츠 개발
          icon: fas fa-vr-cardboard
          description: 3D게임 사용자에게 더 현실감을 느낄 수 있도록 하는 VR컨텐츠에 대해 관심이 있습니다.
        - name: 인공지능 관련 기술들
          icon: fas fa-robot
          description: 자연어 처리, 딥러닝 등의 기술을 게임에 적용하여 사용자와 게임 내 인물의 상호작용을 더 자연스럽게 할 수 있습니다.
        - name: 그래픽 관련 기술
          icon: fas fa-palette
          description: 하이폴리곤을 사용하여 모델을 생성해도 실시간 렌더링이 가능하도록 하는 Unreal5의 나나이트 기술에 대해 공부하고 있습니다.
        - name: 양자 컴퓨팅 기술
          icon: fas fa-atom
          description: 고퀄리티의 무거운 게임 프로그램을 잘 동작시키기 위해서 더 좋은 성능을 가진 양자 컴퓨팅 기술에 대해 공부하고 있습니다.
        - name: 클라우드 컴퓨팅 관련
          icon: fas fa-cloud
          description: 사용자가 게임을 플레이 하기 위해 필요한 사양 등의 진입장벽을 낮출 수 있는 클라우드 컴퓨팅 기술과 네트워크 기술등에 관심이 있습니다.
  

---
