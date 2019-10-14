# 막차렐라: 막차시간 알림

집으로 가는 대중교통 노선을 선택하면, 막차시간 N분 전에 알려주는 PWA

## 구상

### 예상 기술 스펙

Express, React, ??? 

### 기능

- 현재 장소에서 도착지 까지의 대중교통 노선을 검색하는 기능
- 해당 노선의 막차 시간을 알려주는 기능
- 알림 등록 후 지정 시간에 알림을 주는 기능

## 목표

- PWA 구현
    - HTTPS 연결
    - W3C Manifest
    - Service Worker 사용
    - [Ref 1. 웹 프로젝트는 PWA이어야 한다.](https://webactually.com/2017/09/%EC%9B%B9-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EB%8A%94-pwa%EC%9D%B4%EC%96%B4%EC%95%BC-%ED%95%9C%EB%8B%A41/)
    - [Ref 2. Getting into PWA with React](https://www.youtube.com/watch?v=rAx2x6CSnws)
- 아키텍쳐 이해!
    - NGINX - WAS?
    - elb - S3 or EC2?
    - Ref 1. 해민이형