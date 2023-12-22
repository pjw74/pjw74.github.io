---
title: streamlit를 이용한 설문지 구현
author:
date: 2023-10-23
categories: [side project]
tags: [streamlit, spreadsheet]
---

# streamlit + spreadsheet 연동

아는 형님 부탁으로 간단한 설문지를 구현한 것을 정리

## 정의
1. excel로 작성한 설문지 -> 프린트하는 번거러움
2. 일일이 손으로 작업 -> 작성지를 통합하는 과정의 번거러움
3. 키워드에 대한 wordcloud 작업 -> 새로 추가

## 문제 해결
1. 배포에 대한 내용은 알고 있었다. 하지만 AWS, GCP 쓰기에는 사용자가 많지 않다는 걸 알고 있었음 \
-> 20명 내외
2. 그래서 streamlit으로 배포 작업을 하려고 시도하였다.
3. 로그인 기능, DB 연결, Python 구현 가능 이점이 있어서 streamlit으로 구현하기로 하였다.

## 작업 시작

1. 일단 간단한 public repo 생성, 배포에 대한 내용은 스킵하겠다. (한글로 된 자료가 많음)\
-> 항시 배포에 대한 내용은 docker로 대체하기로 하고
2. spreadsheet, google API 연동 및 인증키 생성 등 내용 작성
3. 문법에 대한 내용 작성

## 결과

1. 스프레드시트 이미지

![img-description](/assets/img/1.png)








[참고 1](https://www.youtube.com/watch?v=HwxrXnYVIlU)
[참고 2](https://www.youtube.com/watch?v=xQwDfW7UHMo&list=TLGGAxN0dA-LUZ8wNDEyMjAyMw&t=370s)

