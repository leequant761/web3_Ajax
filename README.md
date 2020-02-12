# web3_Ajax
https://opentutorials.org/course/3281

https://leequant761.github.io/web3_Ajax/index.html

## 목적

Single Page Application이라는 유사 애플리케이션을 만들게 된다.

애플리케이션이라는 것은 동적이고 하나의 html로 모든 페이지를 나타내는 문서를 의미하고 

유사라는 것은 검색엔진에 노출되기 때문에 애플리케이션은 아니다라는 걸 의미한다.

구글 홈페이지를 킨 다음에 검색어를 입력하면 추천 검색어가 나오는데 과연 첫 로딩할 때 이 목록이 다운로드되었을까?

클라이언트가 검색어를 입력하면 웹브라우저와 웹서버가 통신을 한 뒤에 받은 것을 부분적으로 갱신하는 것이다.

그래서 목적이라 한다면 

> "html에서 바뀔 수 있는 부분을 fetchAPI을 사용하여 Asynchronous JavaScript and XML를 구현하자"

## 키워드

`fetch` `then` `callback` 비동기 익명함수

## 부작용

주소가 안바뀜 ==> 다른 사람에게 내가 보는 페이지를 공유할 수 없음 ==> `location.hash`

## 또 다른 부작용

검색엔진에 노출이 안된다 ==> pjax(여기선 안배움)를 사용하자

> 웹페이지 자체는 비었고 백엔드에서 동적(클릭할 때)으로 가져오니깐

## 애플리케이션과 데이터를 따로 뗴어놓자

## polyfill

fetchAPI는 최신 기술이라 구식 브라우저에서는 지원하지 않는다. ==> https://github.com/github/fetch

## ajax의 확장

pjax for 검색엔진

progressiv web application for offline + online
