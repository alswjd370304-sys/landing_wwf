# 랜딩페이지-wwf 북극곰 후원하기
26/07/20 ~ 
* 반응형 웹 breakpoints: mobile(440) tablet(1024) PC(1920)
* 사용스킬: figma, html, css, javascript
## 페이지 구성 & 주의사항 & 공부 기록
1. landing_wwf/index.html`.intro`
    * background-img와 background-color는 한 요소에 들어갈 때 순서를 변경할 수 없다. -> 배경이미지와 배경색상이 들어가는 각각의 요소를 별도로 생성해야함. -> 배경이미지가 태그에 들어간다면 배경색상은 가상요소(after, before)활용하기
    * 배걍색상(단색)이 아닌 경우 배경색(그라데이션)이라면 -> background-color가 아닌 background 통합속성을 사용해야함을 주의하기!
    * background-color는 한가지 단색만을 지정하기 때문에 그라이데이션을 사용할 수 없음.