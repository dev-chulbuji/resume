![GitHub last commit](https://img.shields.io/github/last-commit/dev-chulbuji/resume.svg)
[![HitCount](http://hits.dwyl.com/dev-chulbuji/resume.svg)](http://hits.dwyl.com/dev-chulbuji/resume)

# 이력서

## Introduce
- Name: 김동진(dj.kim)
- Email: ladmusician.kim@gmail.com
- Github: https://github.com/dev-chulbuji

## Experience
- [카카오뱅크](https://www.kakaobank.com/) (19.04 - )
- [Flitto](https://www.flitto.com/) (18.11 - 19.02)
- [개인카페 창업 & 플리랜서](https://www.instagram.com/__zipdri/) (17.10 - 18.10)
- [Vingle](https://vingle.com) (17.06 - 17.10)
- [Goqual](https://www.goqual.com/) (15.02 - 17.04)
- ClasseStudio( 13.07 - 14.07)

## Skill Stack
- docker container
- kubernetes
- nodejs
- python
- bash
- yaml

## Activity
- [Kubernetes Scheduler - Open Infrastructure & Cloud Native Days Korea 2019 발표](https://drive.google.com/file/d/1bqkUrXOEUvNZxf0iXghlPZ5DSJhRZ85t/view?usp=sharing)
- [Kakaobank - Kubernetes 사내 발표](https://docs.google.com/presentation/d/1kOCsAngKGZpHvFVeS227cXsfFfPVlNWdtjaq5S1NDsg/edit#slide=id.g51229b7dc5_2_967)
- AWS KRUG - Kubernetes 보안 발표
- [Flitto - Terraform 도입 사내 발표](https://docs.google.com/presentation/d/1VZvGsXjXc2EcJL6P_j0jUiUqF55HLvLwGNzLG00DIOw/edit?usp=sharing)

## Project
>**금융권 환경에 맞는 Docker echo system 구축&고도화 | 카카오뱅크**
- Docker container registry 운영
  - Harbor v2.0.0
  - Harbor custom prometheus exporter for robot account
- Docker container CI/CD 플랫폼 고도화
  - Ansible 기반의 배포 환경 고도화
  - 무중단 배포 기능 추가(BLUE/GREEN)
- Docker cli 통제
  - hbm 오픈소스 고도화
- Docker container 모니터링 환경 고도화
  - prometheus & grafana (metric)
  - elasticsearch & kibana (logging)
  - consul (service discovery)
---
>**금융권 퍼블릭 클라우드 도입 | 카카오뱅크**
- Terraform, Ansible 등을 이용한 운영 자동화 환경 구축
- EKS 구축 및 운영정책 수립
  - terraform script 작성
  - 운영/사용 가이드 작성
---
>**금융권 프라이빗 클라우드 쿠버네티스 도입 | 카카오뱅크**
- 금융권 컴플라이언스를 준수하는 Kubernetes 클러스터 구축
  - Ansible 기반의 provisioning script 작성
  - 운영/사용 가이드 작성
- Kubernetes 모니터링 구축
  - prometheus & grafana (metric)
  - elasticsearch & kibana (logging)
---
>**사내 관리용 서비스 업데이트 및 쿠버네티스 관리 | 플리토**
- 사내 데이터 관리용 서비스 업데이트
- framework 변경
  - tsed framework -> nestjs framework 변경
  - sequelize orm -> typeorm
  - unit test 작성
- 사내 e2e 테스트 환경 구축 및 테스트 기능 구현
- 자동화 시스템 구축
  - AWS nacl 수동 -> AWS nacl 자동(terraform, slack, jenkins)
- Docker image 경량화
  - Alpine linux
  - multi-stage docker build
---
>**안드로이드 클라이언트 앱 업데이트 | 빙글**
- 대규모 업그레이드 TF 참여(involve 33%)
- 안드로이드 배포 CI/CD jenkinsfile 고도화
- 안드로이드 프로젝트 디자인패턴 변경
  - MVC -> MVP pattern
  - Presenter layer unit test 작성(JUnit)
---
>**원격제어 스마트 스위치 소프트웨어 구현 | 고퀄**
- BLE(블루투스) 통신을 위한 펌웨어 개발(C++, cc2540)
- 스위치 제어 클라이언트 앱 개발(Android)
- 스위치 제어 백단 서버 개발
  - api server (nodejs, express, mysql)
  - mqtt server (mosquito)


---
여기까지 읽어주셔서 감사합니다. 더 궁금하신 내용이 있다면 ladmusician.kim@gmail.com으로 연락주세요.
감사합니다 :)