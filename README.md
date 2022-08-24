# react_movieInfoWeb_free
# 영화 사이트 클론 by nomad coder
---

- 진행상황
  - /14-1 (5%) - 220825

- 강좌 정리
  - 규칙
  - app 실행 관련
  - 리액트 대체 범위 


- js knowledge
  - [querySelector](https://www.daleseo.com/js-document-query-selector "관련 문서")
  - - html 요소중 첫번째만 가져오고 전부다 가져오는건 `querySelectorAll`
  - - 불특정 element 다 가져올수 있음.
    - return value : baseElement의 자손 element을 가져옴. 이 때 js로 html을 조작 가능.

- react knowledge
  - react-dom : react elem들을 html body에 배치시키는 lib.
  - react는 engine느낌으로써 interactive한 ui를 만들게한다.
  - `render()`는 rea elem로 html를 만들어 배치함.
    - 1 param : render 될 elem
    - 2 param : where to put, 보통 body에 root div를 생성하고 가져온다.
  - react는 js에서 시작해 html로 만들어진다.
  - user에게 보여줄 내용을 컨트롤한다.그것이 핵심포인트(whole point)
  - js로 만들면 reactJs가 html로 번역한다.