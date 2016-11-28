title: HeXA CTF 2016 Epilogue
date: 2016-11-28 17:50:12
author: SleepyBear
tags:
- SleepyBear
- ctf
- epilogue
---
안녕하세요, 이번 HeXA CTF 2016 운영 총괄을 맡은 HeXA 회장 겸 해킹부장 김동민(SleepyBear)입니다. 아무것도 모르고 Layer7 CTF와 Holyshield CTF에 참여했던 고등학생 때가 엊그제같은데 직접 CTF를 운영하게 되었네요. 

UNIST 교내 학생만들을 대상으로 하는, CTFTime이나 국내 고등학교, 대학교 동아리 개최 CTF들에 비해서는 작은 규모였지만 제게는 문제를 푸는 입장을 넘어서 지금까지 공부한 것을 토대로 출제진과 함께 문제를 만들어 제공하는 기회가 되어 의미있었던 것 같습니다.

## 플랫폼

<p align="center"> <img src="/img/hexactf2016-1.png" style="width: 90%;"/></p>

이번 CTF에서는 페이스북에서 제공한 오픈소스 CTF 플랫폼을 사용해보았습니다. 실시간 스코어보드 및 그래프, King of the Hill(거점점령)문제 지원, Quiz 지원(대소문자를 구별하지 않는 단답형 flag), 문제별 Breakthru 지정, Admin Dashboard 기능이 마음에 들어서였습니다.

<p align="center"> <img src="/img/hexactf2016-3.png" style="width: 90%;"/></p>

하지만 대회 당일에 웹사이트 속도가 급격히 느려져서 대회 기간동안 진땀뺐습니다... 테스트때는 스탭들만 접속해봐서 느려진다는걸 전혀 못느꼈거든요. 서버 CPU 점유율이 점점 올라가길래 재부팅도 해보고, hhvm 퍼포먼스 관련 이슈도 해결해보겠다고 조마조마하면서 라이브 패치도 하고… 중간에 플랫폼을 옮길까 생각도 해보았지만 결국 점수 관리때문에 문제만 따로 모아둔 Google Docs를 제공할 뿐이었습니다. 

이 밖에도 준비하는 과정에서 회원가입 시 입력한 이메일이 DB에 저장되지 않는다던가, 스코어보드 그래프가 일정 시간 이후가 표시되지 않는다던가 하는 잔버그들이 너무 많았습니다. OTL. 다음에는 HeXA CTF 2015때 이용했던 플랫폼에 이번에 마음에 들었던 기능들을 추가해서 사용할 것 같습니다.

## 문제

<p align="center"> <img src="/img/hexactf2016-2.png" style="width: 90%;"/></p>

저를 포함한 6명이 총 33문제를 만들었습니다.  저는 포렌식 문제를 좋아해서 포렌식 위주로 문제를 내보았습니다. 포렌식 문제에 주어진 자료를 분석하는 것과 자료를 만드는 것은 전혀 다른 경험이더라구요. 랜섬웨어에 감염되어볼까도 생각해보고, VM 이미지를 어떻게 하면 깔끔하게 만들어 제공할 수 있을까 한참 고민해보기도 했습니다. 결국 이번에 저는 기술적인 문제보다는 트릭을 이용한 문제를 많이 만들었습니다.

가상의 인물을 만들어 신상을 털게 해볼까 하는 아이디어에서 출발한 '레스토랑스의 습격' 문제와 지하철 노선도를 이용한 뿌링클 기프티콘 이벤트문제도 dohan0930이 만들었어요. 재미있는 경험이었고 앞으로 제가 경험한 다양한 사례들을 문제에 녹여낼 수 있게 부지런히 공부해야겠다고 다짐했습니다.

## 마무리

이번에 출제된 문제를 바탕으로 HeXA 멤버들을 위한 워게임 사이트를 만들 계획을 하고있습니다. 이런 문화를 만들어주신 선배님들께 감사하고, CTF에 참여해주신 분들도 모두 감사합니다!