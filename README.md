# css-practice

- 간단한 html과 css를 통해 다양한 레이아웃 배치를 연습해보는 저장소 입니다.

<br />

> ### 구현 예시

<details>
<summary>1. 가상 상위 컴포넌트 가운데 정렬</summary>
<div markdown="1">
<img width="300" alt="스크린샷 2022-03-29 오전 10 01 19" src="https://user-images.githubusercontent.com/79782594/160424120-f6bb3bef-d18b-4ca6-9491-79c02381f572.png"> <br />
- 가장 상위 컴포넌트이므로 position: absolute로 가운데 정렬 시켜줘도 무방.  <br />
- 어차피 하위 컴포넌트들은 이 컴포넌트에 맞춰 따라옴.  <br />
- position:absolute를 지정한 뒤, 정중앙에서 엘리먼트가 시작 되게끔 함.(top: 50%, left:50%) <br />
- 생성된 엘리먼트를 50% 씩 위, 옆으로 다시 이동시킴(transform: translate(-50%, -50%)
  
</div>
</details>

<br />

<details>
<summary>2. 하위 컴포넌트 가로로 정렬하기</summary>
<div markdown="1">
<img width="500" alt="스크린샷 2022-03-29 오전 10 01 19" src="https://user-images.githubusercontent.com/79782594/160517073-413cc2e3-2428-4b1b-8f26-59e14acfd458.png"> <br />
- 상위 컴포넌트에 display:flex를 적용시킨 후, justify-content 속성을 활용.

</div>
</details>

<br />

<details>
<summary>3. 이미지 삽화처리 넣기</summary>
<div markdown="1">
<img width="200" alt="스크린샷 2022-03-29 오전 10 53 29" src="https://user-images.githubusercontent.com/79782594/160517569-e2729974-1085-42b7-bbfe-057fab451efa.png"> <br />
- 해당 이미지 태그에 float 속성을 부여함.  <br />
- margin 값을 넣으면 엘리먼트 간의 간격을 조정할 수 있음.

</div>
</details>

<br />

<details>
<summary>4. li 엘리먼트 구분선으로 나눠주기</summary>
<div markdown="1">
<img width="400" alt="스크린샷 2022-03-29 오전 10 53 29" src="https://user-images.githubusercontent.com/79782594/160532783-1a8d5ba0-e332-4942-9ff6-abe4e3df3ce8.png"> <br />
- ul 엘리먼트에서 list-style:none으로 리스트에 생기는 점 제거.  <br />
- align-items 이용해서 수직 가운데 정렬 (단, 엘리먼트의 height 값을 명시해야 함.  <br />
- before 가상 선택자 이용해서 구분선 만들기.
  
</div>
</details>

<br />

<details>
<summary>5. grid 이용해 엘리먼트 자유롭게 배치하기</summary>
<div markdown="1">
<img width="400" alt="스크린샷 2022-03-29 오전 10 53 29" src="https://user-images.githubusercontent.com/79782594/160539216-9c8e64c3-3b36-4a0c-aabd-a98f09b6fe75.png"> <br />
- display: grid 사용.  <br />
- grid의 시작 여백은 padding 이용하기  <br />
- grid에 들어가는 div 엘리먼트의 수를 알 수 있고, 변하지 않는다면 grid-template 사용.  <br />
- div 엘리먼트의 수를 알 수 없거나, 계속 변화한다면 grid-auto를 사용. <br />
- fr은 주어진 길이를 비율로 나눈 값.
- grid 속성을 사용할 때는 호환성에 주의해야 함.
  
</div>
</details>
