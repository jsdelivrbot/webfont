# NanumBrush
> 구글웹폰트 링크가 나눔브러시가 익스에서만 한글이 적용이 안되서 네이버에서 자체 제공하는 웹폰트를 깃헙에 올려서 링크하였습니다. 구글의 CSS를 살펴보니 woff만 제공되는군요.

> 나눔손글씨 펜체는 깔끔한 선 처리와 생동감이 돋보입니다. 반면 나눔손글씨 붓체는 꾸미지 않은 편안함과 리듬감이 매력적입니다. 2009년 ‘손글씨 공모전’에 응모한 3만 3천 작품 중 대상작으로 뽑힌 정재경 님의 작품을 나눔손글씨체로 개발했습니다. 나눔 손글씨 붓체, 펜체 / 한글 2,350자, 영어 94자, KS약물 986자 http://hangeul.naver.com/2017/nanum

나눔손글씨 붓체 웹폰트 입니다.
[Demo](https://codepen.io/eond/pen/xYjwNg)

## 사용방법

### link 방식 (권장)
	<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/eondcom/webfont/master/NanumBrush/nanumbrush.css">

### import 방식
	@import url(https://cdn.rawgit.com/eondcom/webfont/master/NanumBrush/nanumbrush.css);

## 적용
> 아직 아래는 적용을 안했습니다. -_-; 대단히 귀찮습..

## 옵션
Regular(400), Bold(700), Extra Bold(800), Light(300) 지원됩니다.

### css (예)
	body		{ font-family: 'NanumBrush', sans-serif; }
	.normal		{ font-weight: 400 }
	.bold		{ font-weight: 700 }
	.bolder		{ font-weight: 800 }
	.light		{ font-weight: 300 }
