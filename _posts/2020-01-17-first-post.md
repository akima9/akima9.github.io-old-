---
title:  "github.io 블로그 시작하기"
excerpt: "github.io 블로그 초보를 위한 Tip"

categories:
  - Blog
tags:
  - Tip
---

- 블로그 포스트는 _posts 폴더에 md 파일 확장자를 사용한다.
- jekyll(지킬)이 포스트 글로 인식하는 파일들은 _posts 폴더 밑의 YEAR-MONTH-DAY-TITLE.md 형식의 파일들이다.
- 마크다운 문법
	- 기본적인 텍스트 표기 방식이다.
	마크다운은 줄바꿈을 인식하지 않는다.

	- 줄바꿈을 하기 위해서는 라인 끝에 스페이스 2번
	표기해야 한다.(sublimetext로 작성해본 결과 문서 저장시 스페이스 두번 넣은것이 사라진다..;;)

	- 여러가지 강조 표시가 존재한다.
		1. *single asterisks*
		2. _single underscores_
		3. **double asterisks**
		4. __double underscores__
		5. ~~cancelline~~

	- 글머리 달기 (위에는 라인이 하나 더 떨어졌는데 여기는 왜 안되지??)
		1. # This is a H1
		2. ## This is a H2 (밑에 이상한 라인이 생김..)
		3. ### This is a H3
		4. #### This is a H4
		5. ##### This is a H5
		6. ###### This is a H6

	- 인용
		> This is a blockqute.

		- 단계별 인용
		> This is a first blockqute.
		>> This is a second blockqute.
		>>> This is a third blockqute.

		- 코드 인용
		```javascript
		function test() {
			console.log("notice the blank line before this function?");
		}
		```

	- 수평선
		1. * * *
		2. ***
		3. *****
		4. - - -
		5. -----------------

	- 링크 표시법
		1. [naver](https://www.naver.com)
		2. 주소 직접 표시법
			- <https://google.com>

	- 이미지 삽입
		1. ![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg)
		2. ![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg){: .align-center}
		3. ![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg "키보드"){: .align-center} (대괄호에 키보드 사진이라고 넣지 않아도 나오는데?!)

	- 표 (난 왜이리 작게 만들어져..)

		| 항목 | 가격 | 개수 |
		|:---:|:---:|:---:|
		| 라면 | 800원 | 10개 |
		| 과자 | 900원 | 20개 |

		| 항목 | 가격 | 개수 |
		|:----|:----|:----|
		| 라면 | 800원 | 10개 |
		| 과자 | 900원 | 20개 |
