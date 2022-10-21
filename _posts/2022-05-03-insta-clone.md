---
layout: post
title:  "Instagram Clone coding"
info: "mini project"
tech: "Python, Flask, MongoDB"
type: Toy
---



![logo](https://camo.githubusercontent.com/94b1c3641c1dbabac16cfff75bd7604185177535669be244ef38db5b904acdeb/68747470733a2f2f696d67312e6461756d63646e2e6e65742f7468756d622f523132383078302f3f73636f64653d6d746973746f72793226666e616d653d6874747073253341253246253246626c6f672e6b616b616f63646e2e6e6574253246646e25324663525a7957772532466274724a326e6256304c79253246563074684c36744e6a4a4b6e6b5072487369596c4a4b253246696d672e706e67)




# \[웹소설] 일타강사 AI의 기막힌 추천

네이버 시리즈에서 판매중인 웹소설 작품의 작품정보를 크롤링하여 얻은 줄거리를 자연어 처리를 하여  웹소설의 스토리를 벡터 임베딩을 통해 사용자가 선호한 소설의 줄거리와 유사도가 높은 작품을 추천해주는 서비스

<br>

**프로젝트에 대한 나의 역할** → [**"보러가기👀"**](#프로젝트에-대한-나의-역할-및-경험)

<br>

>[`🔗시연영상`](https://tv.kakao.com/v/429567788)

<br>

|![image](https://user-images.githubusercontent.com/104331869/185335939-524bba9a-0f3c-46a1-bd07-628a852fbab2.png)|![image](https://user-images.githubusercontent.com/104331869/185335986-2b364717-cbd4-4d6b-9d8d-402d934dfaab.png)|![image](https://user-images.githubusercontent.com/104331869/185336258-a03c1dc7-d0c8-450b-8db2-bf3b6d94ec27.png)|![image](https://user-images.githubusercontent.com/104331869/185336306-f071016c-1077-445c-98e0-03f19b8cf29e.png)|
|:---:|:---:|:---:|:---:|
|로그인|회원가입|메인 페이지|장르별 작품 리스트|
|![image](https://user-images.githubusercontent.com/104331869/185338031-62118c95-2fd7-4860-b2da-75ae1f22fcaf.png)|![image](https://user-images.githubusercontent.com/104331869/185337856-1f08eb63-35d1-4712-8d2a-0a13cbaa16a0.png)|![image](https://user-images.githubusercontent.com/104331869/185338071-2d4bd6e3-3b71-4bf8-9525-41ee2b988a0f.png)|![image](https://user-images.githubusercontent.com/104331869/185338306-4d1e7365-9d8c-47bc-ba02-c855c837b2d3.png)|
|검색 결과|작품 상세 페이지|마이 페이지|나의 리뷰 모아보기|

<br>

## 프로젝트 기간

2022-06-02 ~ 2022-06-13

<br>

## 주요 기능

1. Django 내장 모델을 사용한 회원가입/로그인/로그아웃 기능
1. 네이버 시리즈에서 판매중인 웹소설 작품의 작품정보를 BeautifulSoup과 Selenium을 이용하여 크롤링
1. 자연어 처리를 이용해 웹소설의 스토리를 벡터 임베딩
1. 사용자가 좋아한 작품의 줄거리와 유사도가 높은 작품을 추천
    * 등록된 선호작이 없다면 별점이 높은 작품들을 추천
1. 작품에 대한 리뷰 CRUD 기능
1. 리뷰를 분석하여 가장 많은 키워드 5개 표시 (작품 상세 페이지)
1. 좋아한 작품의 스토리 키워드 빈도수 상위 10개 표시 (마이 페이지)

<br>

## 프로젝트 기록

>[`🔗Github`](https://github.com/cmjcum/webtachu)  
[`🔗Starting Assignment (tistory)`](https://cold-charcoal.tistory.com/85)

<br>

## 팀 구성 및 역할

| 이름 | 역할 | 깃허브 |
|:----------|:----------|:----------:|
| **이정아&nbsp;&nbsp;&nbsp;&nbsp;** | 시민증 발급 페이지, 상점 페이지(back), 방 꾸미기 기능, 딥러닝&nbsp;&nbsp;&nbsp;&nbsp;  | [`🔗zeonga1102`](https://github.com/zeonga1102)|
| **노을** |게시판 페이지, 상점 페이지(front), 로고 제작 | [`🔗minkkky`](https://github.com/minkkky) |
| **이현경** | 로그인 및 회원가입 페이지, AWS 배포| [`🔗LULULALA2`](https://github.com/LULULALA2)|
| **김동근** | 마이 페이지 | [`🔗yinmsk`](https://github.com/yinmsk) |

* 모델제작 - 팀 전체 참여

<br>

## 스킬 및 사용툴

`Python`, `Django`, `BeautifulSoup`, `Selenium`,`Colab`, `MeCab`, `Doc2Vec`

<br>
<br>

# 프로젝트에 대한 나의 역할 및 경험


## 나의 역할

**백엔드**

* 


**프론트엔드**

* 


<br>

### 1.

<br>
<br>

# 🧨TroubleShooting


### 1. 

<br>
<br>
<br>

# 회고

>크롤링을 하는 부분에서 생각보다 많은 시간을 잡아먹었다. 깔끔하게 크롤링을 하기위해 고려해야할 것도 많았고, 규칙적이지 않아서 크롤링이 불가능 한 것도 많았다.원래 웹타추로 구현하고 싶었던 것은 사용자의 평점을 기반으로 소설을 추천해주는 협업필터링 방식의 추천시스템이었는데, 유저데이터가 없어서 줄거리를 분석해서 유사도가 높은 웹소설을 추천해주는 방식으로 노선을 변경해서 조금 아쉬웠다. 

>크롤링한 데이터를 기반으로 모델을 테스트해본 결과 줄거리가 유사한 작품을 잘 추천하기는 하지만, 줄거리가 소설의 전체를 잘 반영하기는 어렵기 때문에 작품 분위기나 문체 등을 고려할 수 없어서 실제 서비스를 했을 때 사용자의 만족도가 높을 것 같지는 않았다. 

>프로젝트 후반에는 화면공유를 하면서 세부적인 디자인 변경이나 자잘한 기능을 추가하고, 버그를 즉각적으로 발견하고 나눠서 수정하는 시간을 가졌다. 점점 팀워크도 더 잘 맞는 것 같고, 다들 열정적이라 프로젝트가 더 재미있었던 것 같다.

