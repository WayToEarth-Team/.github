

# 🌍 Way to Earth

**Way to Earth**는 러닝을 통해 실제 거리를 누적하면서, 지도 위에서 가상의 여정을 진행하는 **러닝 기반 여정 시뮬레이션 플랫폼**입니다.
사용자는 러닝 기록을 쌓아가며 가상 코스를 완주하고, 엠블럼을 획득하며, 크루 및 커뮤니티 기능을 통해 동기부여를 이어갈 수 있습니다.

---

## 🚀 주요 기능

* **싱글 러닝**

  * 실시간 거리, 페이스, 칼로리 측정
  * 지도 경로 표시 및 기록 저장

* **가상 러닝 (Virtual Course)**

  * 출발–도착지 기반 가상 코스 진행
  * 누적 거리 기반 진행률 계산
  * 완주 시 엠블럼 지급

* **피드 & 커뮤니티**

  * 러닝 기록 공유, 댓글/좋아요 기능
  * 크루 생성 및 가입, 크루 랭킹 & 대결

* **엠블럼 시스템**

  * 완주·도전 과제를 달성해 다양한 엠블럼 수집
  * 프로필에서 수집률 확인 가능

* **AI 인사이트 (추가 예정)**

  * 주간 러닝 데이터를 기반으로 동기부여 메시지 제공

---

## 🛠 기술 스택

* **Frontend**: React Native (Expo, TypeScript)
* **Backend**: Spring Boot (Java 21, JPA, QueryDSL)
* **Database**: MariaDB (AWS RDS)
* **Infra**: AWS (EC2, S3, ALB, Docker, GitHub Actions)
* **Auth**: Kakao OAuth 2.0 + JWT
* **Realtime**: WebSocket
* **Push**: Firebase Cloud Messaging

---

## 📌 프로젝트 구조

```bash
way-to-earth/
 ├── backend/        # Spring Boot API 서버
 ├── frontend/       # React Native 앱
 ├── docs/           # ERD, API 명세, 기획 문서
 └── infra/          # Docker, CI/CD, 배포 스크립트
```

---

## 📖 시작하기

```bash
# Backend
cd backend
./gradlew bootRun

# Frontend
cd frontend
npm install
expo start
```

---

## 👥 팀

* Backend: 2명
* Frontend: 1명

---

## 📌 라이선스

이 프로젝트는 학습 및 연구 목적의 캡스톤 디자인 프로젝트입니다.

---
