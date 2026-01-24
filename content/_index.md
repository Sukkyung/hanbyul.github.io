---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '2rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      headings:
        about: "Bio"        # ← About 헤더 텍스트 비움
        education: "Professional"    # (이미 한 것)
#        interests: ""    # (있다면 같이)
      show_about: false  # ← 이 한 줄이 핵심 (아이콘까지 제거)



    # ✅ 여기부터가 핵심: bio를 me.yaml에서 읽지 말고,
    # 이 블록 text로 직접 표시하게 함 (문단 유지)
      text: |-
         
        👉 **[카카오톡 오픈채팅방으로 1:1 상담하기](https://open.kakao.com/o/ss4PeWci)** 🎶
        
        안녕하세요! 😊 서울/송도 소재 초등학교·고등학교 방과후 수업부터 국제학교 학생, 성인 취미생까지 다양한 연령과 수준의 학생들을 개인 맞춤형으로 지도하고 있는 바이올린·비올라 강사입니다.

        🎻 저는 경희대학교에 18살에 조기 입학하여 졸업 후 현재까지 12년간 개인 레슨 및 학교 방과후 교사, 오케스트라 강사로 활동해오고 있으며,

        🎻 아이유, 정승환, LUCY 밴드, 소수빈, 폭싹속았수다 OST 등 국내 아티스트 음원 녹음에 참여하며, 클래식 뿐만 아니라 K-pop, 드라마 OST 등 다양한 장르를 넘나드는 음악적 경험을 쌓아오고 있습니다.
  
        🎻 수업은 학생 한 명, 한 명의 수준과 성향에 맞춘 맞춤형 티칭으로 진행됩니다. 특히 바른 자세와 기본기는 연주의 가장 중요한 토대이기 때문에 초보자 분들도 무리 없이, 정확한 자세로 배울 수 있도록 꼼꼼하게 지도합니다.
  
        🎻 또한 취미로 악기를 배우는 분들이 흥미를 잃지 않도록 OST, 팝송, 원하는 곡 등 다양한 레퍼토리를 활용하여 즐기면서 실력을 쌓을 수 있는 수업을 지향합니다.
  
        🎻 저는 수업 시간 하나하나를 소중히 여기며, 학생들이 가장 효율적으로, 그리고 음악을 즐기며 성장할 수 있도록 최선을 다해 함께하겠습니다 💛
  
        📩 언제든지 편하게 문의 주세요! 개개인에 맞는 맞춤 수업으로 도와드리겠습니다 🎶
    design:
      background:
        gradient_mesh:
          enable: true
      columns: '2'

  - block: markdown
    id: education
    content:
      title: '👩🏻‍🏫 교육 경력'
      subtitle: ''
      text: | 
        - 레슨 경력 12년차
        - 송도 포스코 사내 바이올린 강사 
        - 인천 해밀학교 바이올린, 비올라 강사 
        - 서울 은광 여자고등학교 비올라 강사 
        - 서울 대진여자고등학교 오케스트라 강사 
        - 서울 용문고등학교 방과후 수업 강사 
        - 경희 한의대 선음 오케스트라 강사 
        - 서울 수암초등학교 오케스트라 강사

        초등학교부터 대기업 성인반까지 다양한 연령과 수준의 
        학생들을 지도해왔습니다.
    design:
      columns: '1'
  - block: collection
    id: discography
    content:
      title: 💿 음반 경력
      count: 0
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 3
      show_date: false          # ← 날짜 숨김
      show_reading_time: false  # ← "1분 읽기" 숨김
      show_authors: false       # ← (선택) 한별 이름도 숨김

#  - block: collection
#    content:
#      title: Recent Publications
#      text: ''
#      filters:
#        folders:
#          - publications
#        exclude_featured: false
#    design:
#      view: citation

  - block: markdown
    id: performances
    content:
      title: '🎻 연주 경력'
      subtitle: ''
      text: | 
        - 한국문화예술위원회 주관 ‘찾아가는 음악회’
        - 코리안심포니오케스트라 오페라 「삼손과 데릴라」 
        - KSO 국제지휘콩쿠르 결선-코리안심포니오케스트라 
        - 경희대학교 챔버 오케스트라 협연 
        - 광진문화재단, 동대문구청 등 공공·문화기관 연주를 포함한 다수의 연주 및 공연 활동 경험 
    design:
      columns: '1'

  - block: markdown
    content:
      title: '🎙️ 세션 및 방송·영화 연주 경력'
      subtitle: ''
      text: | 
        - KBS 임영웅 단독 콘서트 「We’re Hero」 
        - 영화 「말할 수 없는 비밀」 리메이크
        - 크러쉬 「Everything happens to me」 MV
        - 넷플릭스 드라마 「반짝이는 워터멜론」
        - SBS 드라마 「브람스를 좋아하세요」
        - OCN 드라마 「작은 신의 아이들」
        - Mnet 「엠카운트다운」 – ASTRO 〈피어나〉
        - KBS 「나는 대한민국」 – 이승철 〈그런 사람 또 없습니다〉
        - KBS 「불후의 명곡」 – 서지안 & 서제이 〈돌아가는 삼각지〉
    design:
      columns: '1'

  - block: collection
    id: photos
    content:
      title: 🎞️ 사진 모음
      count: 0
      filters:
        folders:
          - events
        featured_only: true
    design:
      view: article-grid
      columns: 1
      show_date: false          # ← 날짜 숨김
      show_reading_time: false  # ← "1분 읽기" 숨김
      show_authors: false       # ← (선택) 한별 이름도 숨김


#  - block: cta-card
#    demo: true # Only display this section in the HugoBlox Kit demo site
#    content:
#      title: 👉 Build your own academic website like this
#      text: |-
#        This site is generated by HugoBlox Kit - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.
#
#        <a class="github-button" href="https://github.com/HugoBlox/kit" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/kit on GitHub">Star</a>

#        Easily build anything with blocks - no-code required!

#        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
#      button:
#        text: Get Started
#        url: https://hugoblox.com/templates/
#    design:
#      card:
        # Card background color (CSS class)
#        css_class: 'bg-primary-300 dark:bg-primary-700'
#        css_style: ''
---
