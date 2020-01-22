---
title:  "DB SELECT TIPS"
excerpt: "데이터베이스 초보를 위한 Tips"
toc: true
toc_sticky: true
toc_label: "DB SELECT TIPS"

categories:
  - DB
tags:
  - Tip
---

## chr()
함수 인자에 대응하는 문자를 나타내는 함수

|  종류   |           내용            |
| :-----: | :-----------------------: |
| chr(9)  |            탭             |
| chr(10) |     라인피드(줄바꿈)      |
| chr(13) | 캐리지리턴(행의 처음으로) |



- 활용
```sql
replace(칼럼명, chr(9), '') --탭을 없앤다.
replace(칼럼명, chr(10), '') --줄바꿈을 없앤다.
replace(칼럼명, chr(13), '') --행의 처음으로 보내는 것을 없앤다.
```

## SELECT 후 바로 수정 가능한 쿼리문

```sql
SELECT A.ROWID, A.* FROM 테이블명 A
```