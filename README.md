# UP DOWN

실시간 토론 및 투표 앱 - 엘리스 Flutter 앱 개발 트랙 2차 팀 프로젝트

## 프로젝트 소개

특정 인물에 대한 의견을 실시간으로 토론하고 투표하는 기능을 제공하는 앱입니다. 사용자들은 실시간으로 토론하며 의견을 나누고, 투표를 통해 해당 인물이 '잘못했다'고 생각하는지 여부를 결정합니다. 이 프로젝트는 Firebase Firestore와 Storage를 활용한 실시간 채팅 및 이미지 공유 기능을 중심으로 구현하였습니다.

## 개발 기간

2024.09 - 2024.10

## 기술 스택

- **언어:** Dart, Flutter
- **상태관리:** Riverpod
- **아키텍처:** MVVM
- **라이브러리:**
  - build_runner
  - cloud_firestore
  - firebase_auth
  - freezed
  - go_router
  - image_picker
  - kakao_flutter_sdk_user
  - riverpod_generator
  - firebase_storage

## 주요 기능

### 1. 이미지 공유 기능
- image_picker 라이브러리를 사용하여 기기에서 이미지 선택
- Firebase Storage에 이미지 저장
- Firestore에 저장된 URL을 통해 채팅방에서 실시간 이미지 공유

### 2. 실시간 투표 및 결과 반영
- Firebase Firestore를 통한 실시간 투표 시스템
- 투표 후 재투표 불가능 설정
- 실시간 투표 결과 화면 표시

### 3. 실시간 채팅 기능
- Firebase Firestore 기반 실시간 메시지 저장 및 업데이트
- 실시간 의견 교환 및 투표 참여

### 4. 채팅방 관리
- 관리자 권한을 가진 운영진만 채팅방 생성 가능
- 일반 사용자는 생성된 방 참여 가능

## 팀 구성 및 역할

총 4명의 Flutter 개발자로 구성

### 담당 파트 별 역할

#### 팀장 - 국한
- 투표 결과 기능
- FCM 푸시 알림 기능
- Facebook 소셜로그인
- 시연 영상 촬영

#### 김동혁
- 채팅방 기능
- 채팅방 내 투표 기능
- Kakao 소셜로그인
- 전체 코드 리팩토링

#### 도지훈
- 홈 화면 기능
- 이미지 첨부 기능
- 세부 UI 수정
- 디자인 총괄 / 발표자료

#### 이영인
- 로그인 인증 기능
- Google 소셜로그인
- 마이페이지/설정 기능
- 세부 UI 수정

## 프로젝트 링크

- GitHub: [https://github.com/jhdodev/elice-2nd-updown](https://github.com/jhdodev/elice-2nd-updown)
- 시연 영상: [YouTube Link](https://www.youtube.com/watch?v=7aey9BieNr8)
