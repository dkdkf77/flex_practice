# flex_practice

패스트 캠퍼스 font-end 강의 중 flex 속성에 대한 공부

<hr>

container 스크린샷 넣기

<h3>❗ div는 블록 요소로 수직으로 쌓이는 성격을 가지고 있다.</h3>
부모 요소에 디스플레이 값을 flex를 주면 flex container

그리고 그 안에 자식 요소는 flex items가 된다.

<hr>

<h3>❗️ 부모 요소에 넣을 수 있는 속성</h3>
display, flex-flow, flex-direction, flex-wrap, justify-content, align-content, align-items
<h3>❕ 자식 요소에 넣을 수 있는 속성</h3>
order, flex, flex-grow, flex-shrink, flex-basis, align-self

<hr>
<h3> 각 속성에 대해 알아 보자</h3>
<h4>display = Flex Container의 화면 출력(보여짐) 특성 (flex, inline-flex)</h4>

flex 스크린샷 넣기

flex 속성은 items 가 인라인으로 되고

inline 스크린샷 넣기

inline-flex 속성은 부모인 container 가 인라인으로 된다

<h4>flex-direction = 주 축을 설정 (row, row-reverse, column, column-reverse)</h4>

<h3>row</h3>

row 스크린샷

<h3>row-reverse</h3>

row-reverse 스크린샷

<h3>column</h3>

column 스크린샷

<h3>column-reverse</h3>

column-reverse 스크린샷

<h3>주축을 기준으로 하는 시작점과 끝 점 (Main-axis, x축)</h3>

flex-direction 을 row로 할시 시작 점은 주축의 왼쪽 편
flex-direction 을 row-reverse로 할시 시작 점은 주축의 오른 편

<h3>교차 축을 기준으로 하는 시작점과 끝 점 (cross-axis, y축)</h3>

flex-direction 을 colum으로 할시 시작 점은 top
flex-direction 을 colum-reverse로 할시 시작 점은 bottom
