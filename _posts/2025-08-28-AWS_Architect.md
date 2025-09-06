---
layout: single
title: "AWS 아키텍쳐 강의 요약"
date: 2025-08-28
cartegories: [AWS_SAA]
tag: [AWS, SAA]
---
AWS_ASS 강의 요약
===
- - -
강의 자료: <https://courses.datacumulus.com/downloads/certified-solutions-architect-pn9>
- - -

AWS Cloud는 어디서든 어떤 기업이든 사용될 수 있다.

넷플릭스, 맥도날드, 21세기 폭스, 엑티비젼 등 많은 기업들이 AWS Cloud를 사용하고 있다.
- - -

### AWS Cloud 활용 예시

* 클라우드를 백업, 저장소 용도로 활용
* 빅 데이터 분석
* 웹사이트 호스팅
* 모바일 앱 백엔드 만들기
* 게임 서버를 클라우드로 구동

- - -
### AWS 구조

* AWS Regions
* AWS Availability Zones
* AWS Data Centers
* AWS Edge Locations / Points of Presence

- - -
### AWS Regions

us-east-1, ap-northeast-2 이런 것들이 AWS 리전이다.

##### *리전을 선택할 때는 무슨 기준이 필요한가?*

* 규정 - 정부가 데이터를 해당 국가에 두길 원한다면 리전을 그 지역에서 실행해야 한다.
* 레이턴시 - 사용자가 사용중인 리전과 거리가 가까워야 지연이 적어진다.
* 리전 서비스 - 모든 리전이 모든 서비스를 제공하지 않는다.
* 가격 - 리전마다 가격이 다를 수 있다.

- - -
### AWS Availability Zones(AZ)

각 리전에는 3~6개의 AZ가 있다.    
예시
* ap-southeast-2a
* ap-southeast-2b
* ap-southeast-2c

각각의 AZ는 하나 이상의 독립적인 데이터 센터로 구성되어있다.

- - -
### AWS console

* AWS 글로벌 서비스
  * IAM
  * Route 53
  * CloudFront
  * WAF
* AWS 리전 범위 서비스
  * EC2
  * Elastic Beanstalk
  * Lambda
  * Rekognition

  