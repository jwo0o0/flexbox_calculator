# flexbox_calculator
flexbox를 사용해 html, css, javascript로 동작하는 계산기 만들기

## html/css, flex로 계산기 만들기
(js 파일은 미업로드)

### figma로 mockup / wireframe 제작
<img src="https://user-images.githubusercontent.com/70098708/177490892-e7b29b7a-dbc7-4ba0-b4b0-63d5f6eb1aba.png" width="80%"/>

### 계산기 동작
<video src="https://user-images.githubusercontent.com/70098708/177488317-f3b83d7b-69af-4cbe-af4c-d6ac62327fcf.mov" type="video/quicktime">
</video>

### flex
- display:flex로 설정 후 flex-direction 속성으로 각 button__row들 정렬
- justify-content, align-items 속성으로 계산기와 각 button 요소들 가운데 정렬

### 기능
- 기본적인 사칙 연산 가능
- '=' 버튼을 여러번 누를 시 앞선 결과값에 이어서 연산
  ex) 3, +, 3, =, =, =, = -> 15 출력
- '=' 버튼을 누르지 않고 계속해서 연산 가능 / 연산 중간 결과 값을 계속해서 화면에 업데이트
  ex) 1, +, 2, +, 3, +, 4, +, 5, = -> 15 출력
- '.' 버튼은 연속해서 입력되지 않음
- 연산자 버튼은 연속해서 입력해도 마지막에 입력한 걸로 적용해서 연산

### css
- :hover, :active 가상 선택자로 버튼에 커서가 있을 때, 눌렀을 때 효과
