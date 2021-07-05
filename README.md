<br><br><br>
<p align="center">
<image width="100px" src="/minu-logo.png"/>
</p>
<br><br><br>


# minu-template
노션노션한 웹 템플릿, 미누 <br><br>

[소개](##소개)

[사용법](##사용법)

[도큐먼트](##도큐먼트)

[라이센스](##라이센스)

<br><br>

## 소개
미누 템플릿은 [노션(Notion)](https://notion.so)의 영향을 받아 만들어진 웹 템플릿입니다. <br>

노션의 문서 작성과 공유 기능은 매우 강력하지만 <br>
그만큼 무겁고 자유도가 떨어진다는 큰 단점이 있습니다.<br>

따라서, 가볍고 자유도를 높이면서도<br>
노션의 편의성과 그 디자인을 잃지 않는 웹 템플릿을 만들자 라는 <br>
목표를 가지고 이 템플릿을 만들게 되었습니다.<br>

미누 템플릿은 노션의 거의 모든 디자인 요소를 그대로 승계함과 동시에 <br>
자유도를 더 높이며 편의성을 살린 웹 템플릿입니다.<br>

또한 [fullpage.js](https://github.com/alvarotrigo/fullPage.js/)를 이용하여 풀페이지 스크롤이 가능하도록 제작했으며,<br>
모바일 반응형 또한 지원하여 언제 어디서든 편하게 페이지를 읽을 수 있도록 설계했습니다.<br>

노션노션한 웹 템플릿, 미누를 이제 시작해보겠습니다.<br>

<br><br><br><br>

## 사용법
1. 깃허브에서 코드 다운로드<br>
   미누 템플릿은 cdn 등의 기능을 지원하지 않습니다..<br>
   따라서 깃허브에서 코드를 직접 다운받고 이를 수정하셔야합니다. <br><br>
   코드 다운은 이 페이지 상단 오른쪽 부분의 초록색 버튼을 눌러 zip 파일을 받으면 됩니다.<br>
<br><br>
2. minu-template.html 파일 수정하기<br>
   해당 파일에는 예시 페이지 소스가 들어있습니다.<br>
   이를 참고하여 본인이 원하는 내용으로 수정하면 됩니다.<br>
   자세한 명세는 [도큐먼트](##도큐먼트)를 참고해주세요.<br>

<br><br><br><br>

## 도큐먼트
### 기본적인 사용법
미누 템플릿에서의 요소는 모두 `class`를 통해 관리됩니다.<br>
별다른 수식 없이 `이렇게` 코드블럭이 나온다면, <br>
이는 html 파일에서 `div`와 같은 태그를 선언한 후 삽입하는 `class`의 이름입니다.<br>

미누 템플릿은 `div` 태그에 `class = "something"`을 삽입하는 방법으로,<br>
`<div class="something>어떤 내용</div>` 이렇게 사용할 수 있습니다.<br>

<br><br>

### 라이트모드 / 다크모드
미누 템플릿은 '라이트모드'와 '다크모드'를 사용할 수 있으며,<br>
페이지의 배경색과 글자색을 조정할 수 있습니다.<br>
모드 선택은 각 세션마다 가능합니다.<br>

라이트모드 : `light-mode`<br>
다크모드 : `dark-mode`<br>
예시 : `<div class="container dark-mode">`<br>

<br><br>

라이트모드 / 다크모드를 사용할 경우 <br>
`a` 태그와 `quote`요소를 사용할 때 추가적인 정의가 필요합니다.<br>

`a` 태그 : `a` 태그 `class`에 `light-mode` / `dark-mode`를 추가해주세요.<br>
`quote` : `<div class="light-quote">` / `<div class="dark-quote">` 를 추가해주세요.<br>

<br><br>

### 페이지 폭
미누 템플릿은 '기본적인 폭'의 페이지 뿐만 아니라 '더 넓은 폭'의 페이지도 지원합니다.<br>
폭 선택은 각 세션마다 가능합니다.<br>

기본 폭 : `normal`<br>
넓은 폭 : `wide`<br>
예시 : `<div class="content wide">`<br>

<br><br>

### 정렬
미누 템플릿은 '왼쪽 정렬', '가운데 정렬', '오른쪽 정렬'을 모두 지원합니다.<br>
정렬 선택은 각 요소마다 가능합니다.<br>

왼쪽 정렬 : `left`<br>
가운데 정렬 : `center`<br>
오른쪽 정렬 : `right`<br>
예시 : `<div class="content wide">`<br>

<br><br>

### 텍스트 (h1, h2, h3, small-text)
노션에서 사용가능한 '타이틀'에 더하여 '작은 글씨'를 지원합니다.<br>

타이틀 : `h1`, `h2`, `h3`<br>
작은 글씨 : `small-text`<br>
예시 : `<div class="h1">미누 템플릿</div>`<br>

<br><br>

### 텍스트 (볼드체, 이텔릭체, 취소선)
미누 템플릿에서는 모든 텍스트에서 '볼드체', '이텔릭체', '취소선' 사용이 가능합니다.<br>

볼드체 : `bold`<br>
이텔릭체 : `italic`<br>
취소선 : `strike`<br>
예시 : `<span class="bold">볼드체</span>`<br>

<br><br>

### 기타 요소 (인용, 구분선, 리스트, 스페이서)
미누 템플릿에서는 노션과 같은 '인용', '구분선', '리스트', '스페이서'을 지원합니다.<br>

인용 : `light-quote` / `dark-quote`<br>
구문선 : `hr`<br>
리스트 : `ul` 태그 & `li` 태그<br>
스페이서 : `spacer`<br>
예시 : `<div class="hr"></div>`<br>

<br><br>

### 글씨색, 배경색
미누 템플릿은 노션에서 사용 가능한 모든 색을 지원합니다. <br>

글씨색 : `gray`, `brown`, `orange`, `yellow`, `green`, `blue`, `purple`, `pink`, `red` <br>

배경색 : `gray-back`, `brown-back`, `orange-back`, `yellow-back`, `green-back`, `blue-back`, `purple-back`, `purple-back`, `pink-back`, `red-back` <br>

<br><br>

### 이미지
미누 템플릿은 이미지의 삽입 및 크기 선택과 정렬을 지원합니다.<br>

이미지 : `img` 태그를 사용합니다.<br>

크기 <br>
아주 작은 크기 : `xsmall`<br>
작은 크기 : `small`<br>
중간 크기 : `medium`<br>
큰 크기 : `large`<br>

정렬<br>
왼쪽 정렬 : `left`<br>
가운데 정렬 : `center`<br>
오른쪽 정렬 : `right`<br>

<br><br>

## 라이센스
