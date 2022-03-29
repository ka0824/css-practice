# css-practice

- 간단한 html과 css를 통해 다양한 레이아웃 배치를 연습해보는 저장소 입니다.

<br />

> ### 구현 예시

<details>
<summary>1. 가상 상위 컴포넌트 가운데 정렬</summary>
<div markdown="1">
<img src="https://user-images.githubusercontent.com/79782594/160424120-f6bb3bef-d18b-4ca6-9491-79c02381f572.png" alt="이미지 없음" />
- 가장 상위 컴포넌트이므로 position: absolute로 가운데 정렬 시켜줘도 무방.  <br />
- 어차피 하위 컴포넌트들은 이 컴포넌트에 맞춰 따라옴.  <br />
- position:absolute를 지정한 뒤, 정중앙에서 엘리먼트가 시작 되게끔 함.(top: 50%, left:50%) <br />
- 생성된 엘리먼트를 50% 씩 위, 옆으로 다시 이동시킴(transform: translate(-50%, -50%)

</div>
</details>
