<!-- untoc -->
경마게임
===
카운터를 이용한 간단한 게임입니다.

<!-- untoc -->
### 목차
<!-- toc orderedList:0 depthFrom:2 depthTo:6 -->

* [1. 게임 방법](#1-게임-방법)
* [2. 개발 플랫폼](#2-개발-플랫폼)
  * [Cyclone V](#cyclone-v)
  * [Quartus II Web edition 13.0 & 13.1](#quartus-ii-web-edition-130-131)
* [3. 버그 리포트(2017/6/16)](#3-버그-리포트2017616)
  * [Cyclone V](#cyclone-v-1)

<!-- tocstop -->


## 1. 게임 방법
<pre>1. 두 명이서 진행하는 게임이다.
2. 게임을 실행 시킨후 Reset 스위치를 이용해 Reset을 한다.
3. Reset 후 Start 스위치를 이용해 게임을 시작한다.
4. 먼저 빠르게 버튼을 연타하여 100을 세는 게임이다.
5. 한 세트에 99~0 까지 버튼을 먼저 누르면 1세트가 승리한다.
6. 총 10세트를 승리하면 최종승리한다.
7. 승리한 쪽에 불이 들어온다.
8. 그 후 Reset을 이용하여 다시 게임을 진행할 수 있다.
</pre>

---

## 2. 개발 플랫폼

### Cyclone V

- Part Number: 5CSEMA5F31C6N

- SW[9]: Reset, SW[6]: Start

- KEY[0]: User, KEY[3]: User


### Quartus II Web edition 13.0 & 13.1
- 맨 처음 시작 당시 13.0을 사용하였다.

- 컴파일 후 .sof 파일이 라이센스 문제로 인해 만들어지지 않아 다음 버전을 사용하였다.

- 게임 개발 당시 13.1 버전을 대부분 사용하였다.

---

## 3. 버그 리포트(2017/6/16)

<pre>정식 개발 일정은 2017/6/14을 기점으로 종료되었다.</pre>

### Cyclone V

 - 매우 빠르게 연타시 키 입력이 무시되는 경우가 있음 (일반적인 빠르기는 용인되는 수준)

 - 매우 빠르게 연타시 가끔씩 숫자가 업 카운팅되는 경우가 있음
