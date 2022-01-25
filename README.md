# Tourist Attraction in Seoul
> HTML/CSS를 중점적으로 활용하여 만든 서울 관광명소 소개 웹 사이트
<p align="center"><img src="https://user-images.githubusercontent.com/69743800/150993762-3cd0ff2d-fe16-412a-a001-aef10e04ed27.JPG" width="190px" height="190px"></img>
<img src="https://user-images.githubusercontent.com/69743800/150994455-7eb53d93-4d44-406c-ada2-94f9b6208cdf.JPG" width="190px" height="190px"></img>
<img src="https://user-images.githubusercontent.com/69743800/150994459-79c2a841-4a6a-49d3-a74c-67c588424984.JPG" width="190px" height="190px"></img></p>
<hr>

## 1. 페이지 구조
- 메인 페이지 : 서울의 전도를 보여줌으로써 어느 위치에 어떤 지역이 있는지 한 눈에 알아볼 수 있도록 함
  > 상단: 페이지 제목과 현재 시간을 표시   
  > 중앙: 서울의 전도와 강북과 강남을 나누어 나타내고 하단에는 로그인 버튼 표시   
  > 하단: 제작자명 노출   

- 서브 페이지 : 각각의 지역마다 관광 명소를 사진과 설명을 통해 소개하였고, 다른 페이지로의 이동 또한 용이하도록 설계함
  > 상단: 페이지 제목 – 포인터를 올릴 시 메인 화면으로 복귀   
  > 좌측: 현 지역을 보여주고 포인터를 올릴 시 그 외 지역을 나타내는 리스트 구성   
  > 우측: 관광명소 이름, 사진, 설명을 순차적으로 구성   
  > 하단: 제작자명 노출   

- 로그인 페이지 : 페이지는 하단에 나와있는 아이디와 비밀번호를 입력 시 메인 페이지로 다시 돌아가고, 만약 틀린 경우엔 알림 창이 나타나도록 함

## 2. 파일 구조
- HTML 파일 구분 :
  - 메인 페이지 : Main.html
  - 서브 페이지 :
    - 강북 지역 : GBn.html
    - 강남 지역 : GNn.html
  - 로그인 페이지 : Login.html
- CSS 파일 구분 : 
  - 메인 페이지 : Mainstyle.css 
  - 서브 페이지 : Substyle.css 
  - 로그인 페이지 : Loginstyle.css

## 3. Javascript 활용
- 현재 시간 : 메인 페이지에서 자바스크립트를 통해 우측 상단에 현재 시간을 표시하도록 구현
- 로그인 : 아이디와 비밀번호를 입력 시 맞았다면 메인 페이지로 돌아가고, 만약 틀린 경우엔 알림 창이 나타나도록 구현
