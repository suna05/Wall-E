---
title: Do it 점프 투 파이썬[1]
layout: post
---

###  Do it 점프 투 파이썬 1일차 공부
| 시간   | 장소 | 진도    | 연습문제  |
|-------|:---:|-----------|-------:|
| 12:00  | 서점 | 책 구매  |         |
| 12:40~17:00  | 카페  | 첫째마당 | p106~109, p138~139   |


| 문제  |  O   |  X |
|-------| ---| --- |
| 문자열1 | O  |     |
| 문자열2 | O |    |
| 리스트1 |  O |     |
| 리스트2 |  O |  X   |
| 튜플1 |     |   X  |
| 딕셔너리 |   | X |
| 집합 | O  |  |
| 변수 | O  |  |
| If문 |   | X |
| While문 |  | X |
| for문 |  | X |

스터디

12시: 교보문고 책 살펴보고 구입

12시 40분 ~ 오후 5시: 스터디(첫째마당:파이썬 기본 문법 익히기:03 제어문까지 연습문제 풀었음)



파이썬 기본 문법 익히기
01장 파이썬이란 무엇인가?
- 공동 작업과 유지 보수가 쉽고 편함
- 개발 속도가 빠르다
Life is too short. You need Python.

파이썬 설치 후 sublime text3로 실행하기

sublime text에 파이썬이 설치된 폴더를 추가한 후 
.py 확장자로 파일을 만든 후
ctrl + B
키를 누르면 python 선택하는 창이 나오는데, 여기서 python을 선택하면
아래 console창이 나타나고 결과를 확인할 수 있다.


[연습문제]
![](https://postfiles.pstatic.net/MjAxODA1MTJfMjk4/MDAxNTI2MTMxMjA4NjM0.kB_xhguWrGlILzIF12sxGNmss7U01r-szvRW9Q0nnTYg.P3nuHq-2Wvl36cO0WNWwvZmjhtaffXPdKbidi_kTSaYg.JPEG.wowsun01/1.JPG?type=w773)
yyyymmdd의 형태로 나와서 1988의 형태로 만들어주려고 "19" 문자열을 더한 후 pin의 첫 번째 문자부터 5번째 문자열까지 뽑음

pin[7]은 7번째 문자를 뽑겠다는 의미

리스트의 정렬은 .sort()와 reverse()로 할 수 있음

![](https://postfiles.pstatic.net/MjAxODA1MTJfMTU5/MDAxNTI2MTMyNDI0NTEz.aoY7YemXApYNuf_s7NN1Y3sihWyeMrGCEz4u1XUHTzMg.Q5OsOycNH1ZkqcJ_8YXdAoXwKP7fBAbP3JOcuXaczVMg.JPEG.wowsun01/5.JPG?type=w773)
처음에는 리스트에서 값을 하나씩 빼와서 ' ' 공백을 넣어줬는데 같이 스터디 한 조원 오빠가 join을 사용한 것을 보고 따라 해봄.

a = a + '4' 했는데 오류 발생... 조원 오빠들의 도움을 받아서 완료

![](https://postfiles.pstatic.net/MjAxODA1MTJfNTcg/MDAxNTI2MTMzNjI0MjM3.XamXP8j8dJ6Su8p_l-tbjsODyemWPgSogFCnDWKHw9og.q8mjlkZIdG4i6CPvFCAiyatEpb03bgDxX2nlPksV0L4g.JPEG.wowsun01/7.JPG?type=w773)
제일 이해안갔던 문제.... pop으로 B를 삭제한 후 이 값을 result에 저장을 하여 print하는게 이해가 안갔었다.. 딕셔너리 a에서 값이 삭제되는 것은 이해가 됐지만 추출하다는 것을 이해못했음..