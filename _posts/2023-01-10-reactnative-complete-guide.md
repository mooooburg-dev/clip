---
title: React Native - Complete Guide
author: mooburg
date: 2023-01-10
category: dev
layout: post
---

## 섹션1: 시작하기
#### 1. 강의에 오신 것을 환경합니다 & 배울 내용
#### 2. React Native란 무엇인가?
#### 3. 온라인 학습 커뮤니티에 가입하세요
#### 4. React Native의 내부 살펴보기
#### 5. React Native 프로젝트 생성하기: Expo CLI vs React Native CLI
#### 6. 새로운 React Native 프로젝트 생성하기
- expo-cli 설치
```bash
$ sudo npm install -g expo-cli
```
- 프로젝트 생성
```bash
$ expo init RNCourse
```  
#### 7. 생성된 프로젝트 분석하기
- app.json - 설정 파일
- App.js - 실행 파일
#### 8. 첫 번째 앱을 실제 기기에서 실행해 봅시다!
```bash
$ yarn start
```
- 디바이스에서 Expo 앱 실행
- 화면 확인!
#### 9. 로컬 개발 환경 설정하기
- Android: [android studio](https://developer.android.com/studio?gclid=Cj0KCQiA1ZGcBhCoARIsAGQ0kkqH8-f8wus-g0ifm-Pgvv37pQnv4VQX25AhEGuNlayKq1_Q3nU2MfIaAlMkEALw_wcB&gclsrc=aw.ds) 실행 방법 설명 (android 시뮬레이터)
- iOS: Xcode 설치 및 시뮬레이터 실행 방법 설명
#### 10. 강의 소개
#### 11. 강의 자료, 코드 스냅샷 & 사용 방법
- [Github](https://github.com/academind/react-native-practical-guide-code)

---  
## 섹션2: React Native의 기초 [강의 목표 앱]
#### 12. 모듈 개요
- The Basics
  - React Native 컴포넌트 & UI 다루기
  - Styling React Native Apps
  - Adding Interactivity & Managing State

#### 13. 핵심 컴포넌트 & 컴포넌트 스타일링 살펴보기
- `Text`, `View`는 가장 중요한 내장 컴포넌트
  - div, h2와 같은 html 태그를 사용하지 못한다. DOM을 통해 브라우저에서 작업할 때 사용할 수 있는 HTML 요소라서 네이티브 기기에서는 사용할 수 없다.
  - 공식 문서를 보면 컴포넌트 전체 개수가 많지 않고, 아래의 몇 가지 컴포넌트를 가지고도 충분히 원하는 UI를 만들 수 있다.
  - React Native의 본질은 내장된 핵심 컴포넌트를 다루는 것이다.
- React Native에는 `CSS`가 없다. 브라우저가 아니기 때문에 CSS는 존재하지 않는다. 대신 `Inline Style`을 적용하거나 `StyleSheet` 객체를 사용할 수 있다.

#### 14. 핵심 컴포넌트로 작업하기
#### 15. React Native 앱 스타일링 하기
- `StyleSheet.create()`를 사용해서 스타일 오브젝트를 만들면 IDE에서 코드 힌트를 사용할 수 있다.

#### 16. React Native: 핵심 컴포넌트, 스타일링 & 색상 - 추가 정보
#### 17. 레이아웃 & 플렉스 박스 살펴보기
#### 18. React Native & 플렉스 박스
#### 19. 레이아웃 생성에 플렉스 박스 사용하기
#### 20. 플렉스 박스 - 집중 탐구
#### 21. 레이아웃 개선하기
#### 22. 이벤트 처리하기
- 이벤트 처리 방식은 웹 앱에서 사용하는 방식과 똑같다.
- Button: onClick(X) / onPress(O)
  - 모바일에서는 탭(Tap) 하거나 누른다(Press)
#### 23. (데모 앱 내에서) 강의 목표 리스트 관리하기

