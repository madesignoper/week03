# 🚀 Week 3 문제

## 🤔 문제 설명

서브웨이에 대한 소개 사이트를 만드려고 합니다.

서브웨이 인기 샌드위치를 설명하고, 각각에 대한 정보 및 이미지를 나타낸 HTML파일을 바탕으로 CSS파일을 활용하여 페이지를 꾸며봅니다.
<br>

## 💻 예제 화면

1. [메인 페이지 - `subway.html`](https://madesignoper.github.io/site/week2/)

<br>

## 📌 요구사항

### 0. 공통

- 한글이 깨지지 않도록 해야 합니다.
```sh
<meta charset="UTF-8">
```
- css 파일을 만든 뒤, html과 연결 합니다.
- 예제 화면과 동일한 결과물이 출력되는 html 파일과 css파일을 작성해야 합니다.
- html 기본 페이지 구조에 맞게 작성해야 합니다.
  > html, head, body 태그 사용
- 웹 페이지의 title이 표시되어야 합니다.
  >타이틀은 Sandwich World로 해주세요
- 모든 내용은 태그로 작성되어야 합니다.
  > `<p>안녕하세요</p>` (O) / `안녕하세요` (X)
- google font에서 마음에 드는 폰트를 불러와 적용시켜야 합니다.

### 0. Google Font import 하는 법

* 구글폰트(https://fonts.google.com/)에 들어가서 마음에 드는 폰트를 클릭 한 뒤, 오른쪽에 보이는 `select this style`을 클릭해주세요

* 오른쪽의 `Embed` 탭을 클릭 한 뒤  `link`태그를 포함한 코드를 복사해 html head부분에 추가해주세요

예시)
```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@900&display=swap" rel="stylesheet">
```

* `link`태그의 코드를 복사 한 곳 아래의 코드를 css에 적용하면 끝!

예시)
```css
h1 {
  font-family: 'Roboto', sans-serif;
}
```

### 1. 메인 페이지(HTML 파일)

- head 부분에 css파일과 연결하는 코드를 작성합니다.
- head 부분에 google font를 불러오는 코드를 작성합니다.

### 2. 메인 페이지(CSS파일)

#### html파일에 작성해 놓은 selector 들을 참고하여 다음과 같이 코드를 작성해 보세요

- 전체 배경 색 : #f7d343
- <header> 태그 안

   - 큰 제목(h1)

      - 정렬(text-align) : 가운데
      - 글자 색(color) : #168119
      - 글자 크기(font-size) : 50px
      
   - 본문(p)
      
       - 테두리(border)로  감싸주세요
       - 테두리
           - 두께 : 5px, 두껍게
           - 색상 : #168119
   - 링크(a)
     
        - 링크에 마우스를 갖다댔을 때 : royalblue 색상으로 바뀌기
        - 링크를 방문했을 때 : #168119 색상으로 바뀌기

- <main> 태그 안

    - 서브웨이 인기샌드위치를 나타내는 부분은 가운데 정렬
    - `서브웨이 인기 샌드위치` 글 색상: palevioletred
    - `서브웨이 인기 샌드위치`글 아래 밑줄 긋기(text-decoration 활용)
    - <ol> 태그 안 리스트
       
         - 폰트 굵기: 두껍게
         - 폰트 사이즈 : 1.3em
         - font-style : 기울임체
         - list의 순번을 나타내는 기호 제거 (hint>list-style 활용 =>  인터넷에 검색해 어떤 값들이 있는지 확인해주세요!)
   
   
    - `id : eggmayo` / `id : rotisserie` / `id : club` 각각 테두리(border)로 감싸기
        
         - 각각 다른 색의 테두리로 감싸주세요
         - 테두리 굵기 : 5px / 두껍게
         
   - `설명`부분의 배경색 : papayawhip
   - `칼로리`부분의 배경색 : peru
   - `추천소스`부분(list 포함)의 폰트 색상 : rebeccapurple
   - 배경색은 다르게 지정해도 괜찮습니다!
   
   - 추천소스 리스트 list-style : square (기존의 circle 모양 대신 square로 바꿔주세요)
   
   - 이미지 크기 : width = 전체화면의 30% , height = 전체화면의 20%
   
   
   - `내가 좋아하는 샌드위치를 적어주세요!` 부분에서
       - `input`하는 부분을 클릭하면 배경 색깔이 #168119으로 변환하게 바꾸기
   
- <footer> 태그 안
  
   - 텍스트 정렬 : 오른쪽
   - 5px, 두꺼운 skyblue색 테두리로 감싸기
    
 
## 예상화면
![image](https://user-images.githubusercontent.com/33304898/84216910-c23a2c80-ab05-11ea-8523-8640cda64407.png)

![image](https://user-images.githubusercontent.com/33304898/84216947-dc740a80-ab05-11ea-99d1-54fdf6fb5e16.png)

![image](https://user-images.githubusercontent.com/33304898/84216977-ebf35380-ab05-11ea-99cd-1592ea1a99c8.png)

![image](https://user-images.githubusercontent.com/33304898/84217001-f9a8d900-ab05-11ea-8d9d-95c846ef3537.png)

![image](https://user-images.githubusercontent.com/33304898/84217021-09282200-ab06-11ea-941a-459ddb8c5fe7.png)




## ✍️ 관련 개념

### font

• font-style : 글씨체 지정. 속성값 <normal, italic, oblique> 를 선택 할 수 있다.
   - normal : 기본값
   - italic: : 이탤릭체
   - oblique: 기울어짐꼴
   
• font-variant : 글꼴이 소문자일 경우 대문자로. 속성값 <normal, small-caps(작은 대문자)> 선택 할 수 있다.
   - normal: 기본값
   - small-caps: 소문자를 작은 대문자로 만듦 (소문자를 대문자로 만드는데, 일반 대문자 크기에 비해 더 작다.)
   
• font-weight : 글꼴 굵기. 속성값 <normal, bold, border, lighter, 100~900> 이 있다.
    - normal: 기본값
   - bold: 진하게 표시
    - 100~900 : 숫자 별로 글꼴 굵기를 지정할 수 있음
    - bolder: 상위 요소에서 상속된 굵기보다 더 진하게
    - lighter: 상위 요소에서 상속된 굵기보다 더 흐리게

• font-size: 글꼴 크기. 속성값은 절대값과 상대값 중에서 선택할 수 있다.
    - 절대값: 고정된 크기. 장치에 따라 크기를 조절할 수 없음.
    - px, pt, cm 등의 단위로 지정하거나
     - xx-small, x-small, small, medium, large, x-large, xx-large 중에서 선택
    - medium은 기본값으로 12pt=19px=13m=100%
    - 상대값: 상대적인 크기. 장치에 따라 크기 조절이 가능함.
     - em, %, smaller, larger

웹문서의 경우 기본 글꼴은 %(예:body의 글꼴), 그 외 css 작성은 em으로 사용할 것을 권장합니다.

