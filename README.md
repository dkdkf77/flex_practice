# flex_practice

패스트 캠퍼스 front-end 강의 중 flex 속성에 대한 공부

<hr>

![스크린샷 2021-10-25 오후 4 30 18](https://user-images.githubusercontent.com/88579497/138661486-b3a9df00-c5ec-4b53-8205-1108b1a4169c.png)

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

![스크린샷 2021-10-25 오후 4 43 39](https://user-images.githubusercontent.com/88579497/138661573-01ad6179-ca27-400a-8b7e-19cbbd8d5955.png)


flex 속성은 items 가 인라인으로 되고

![스크린샷 2021-10-25 오후 4 45 07](https://user-images.githubusercontent.com/88579497/138661590-ff0db31e-b3fc-4c2f-a417-63ceade3e239.png)


inline-flex 속성은 부모인 container 가 인라인으로 된다

<h4>flex-direction = 주 축을 설정 (row, row-reverse, column, column-reverse)</h4>

<h3>row</h3>

![스크린샷 2021-10-25 오후 4 52 17](https://user-images.githubusercontent.com/88579497/138661638-b7238b5b-75b8-4510-be32-788ef928f398.png)


<h3>row-reverse</h3>

![스크린샷 2021-10-25 오후 4 55 06](https://user-images.githubusercontent.com/88579497/138661678-6a74536a-950a-4d8d-b9a2-708f6c87e7f8.png)


<h3>column</h3>

![스크린샷 2021-10-25 오후 4 55 23](https://user-images.githubusercontent.com/88579497/138661686-e9f07e2f-b6b7-4a02-a245-cbcae83bfdc1.png)


<h3>column-reverse</h3>

![스크린샷 2021-10-25 오후 4 55 47](https://user-images.githubusercontent.com/88579497/138661708-b9ce1e96-b53a-4843-bb5b-373d6f2a69d9.png)


<h3>주축을 기준으로 하는 시작점과 끝 점 (Main-axis, x축)</h3>

flex-direction 을 row로 할시 시작 점은 주축의 왼쪽 편
flex-direction 을 row-reverse로 할시 시작 점은 주축의 오른 편

<h3>교차 축을 기준으로 하는 시작점과 끝 점 (cross-axis, y축)</h3>

flex-direction 을 colum으로 할시 시작 점은 top
flex-direction 을 colum-reverse로 할시 시작 점은 bottom
