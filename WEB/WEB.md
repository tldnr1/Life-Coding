# 온라인 에디터
https://codesandbox.io/ - VSCode와 닮았고 Github 연동이 된다!! 간단한 페이지 구성보단, 작은 모델 개발에 적합

https://www.programiz.com/html/online-compiler/ - html, css, javascript 만 간단하게 써보기에 좋은 에디터

------------------
# WEB1 - HTML & Internet
- tag란?
    - html 문서를 구성하는 기본 단위

- html의 기본구조
    - head : html의 머리부분
        - title : 웹페이지의 이름. 가장 위에 나오는 부분
        - link : 연동할 파일의 링크 전달. CSS, js 파일 가져올 때 주로 사용
        - script : js를 html에서 작성하기 위한 태그
        - style : CSS를 html에서 작성하기 위한 태그
        - meta : title, link등이 알려주지 못한 메타데이터를 알려주는 부분
            - e.g. charset을 통해 문서를 읽을 언어를 정의할 수 있음
    - body : html의 몸통부분

- 줄바꿈 : br vs p
    - br : 단순 줄바꿈
    - p : paragraph tag로 '한 문단'을 의미  
          주로 p 태그를 많이 이용함

- 링크 태그 : a vs link
    - a : anchor(닻) 이라는 의미로 html에서 다른 페이지와 연결할 때 사용
    - link : 문서나 외부 파일과 연결할 때 사용
    - _href_ : a, link 태그에서 연결할 파일의 URL을 명시
        - href의 속성 값 URL
            - 1. 절대주소 : href=“http://www.tcpschool.com/index.php”
            - 2. 상대주소 : href=“/lecture/logo.png”
            - 3. 같은 페이지 내에서 명시된 id를 가지고 있는 요소 : href=“#bottom”
            - 4. 스크립트 : href=“javascript:alert(‘반갑습니다!’)”
        - target = "_blank" 를 통해 클릭으로 새 페이지 띄우기를 할 수 있다

- 목록 태그 : ol, ul, dl 와 li  
    li는 list item의 약자로 목록을 만드는 태그
    - ol : ordered list의 약자로, 순서가 있는 목록을 만들 때 사용
    - ul : unordered list의 약자로, 순서가 필요 없는 목록을 만들 때 사용
    - dl : definition list의 약자로, 사전처럼 용어를 설명하는 목록을 만듬

- 사진(이미지) 태그 : img
    - src에 사진의 url을 넣어서 사진을 불러올 수 있다
    - width 등과 같은 속성을 통해 사진의 표현을 조절할 수 있다